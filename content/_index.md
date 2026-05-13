---
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      username: admin

  - block: skills
    content:
      title: Skills & Expertise
      text: ''
      username: admin
    design:
      columns: '2'

  - block: skills
    content:
      title: ''
      text: ''
      username: admin2
    design:
      columns: '2'

  - block: portfolio
    id: Current Projects
    content:
      title: Projects
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Neurodegeneration
          tag: Neurodegeneration
        - name: Burns & Trauma
          tag: Burns
        - name: Gut-Brain Axis
          tag: Gut-Brain Axis
        - name: Methods
          tag: Metabolomics
    design:
      columns: '2'
      view: card

  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card

  - block: collection
    content:
      title: Full Publication List
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

  - block: accomplishments
    content:
      title: 'Awards & Honours'
      subtitle:
      date_format: Jan 2006
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2024-01-01'
          description: 'Recognises scientists who combine research excellence with sustained commitment to communicating science beyond the laboratory.'
          icon: ''
          organization: Australian Institute of Policy and Science
          organization_url: 'https://aips.net.au'
          title: Young Tall Poppy Science Award
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2021-01-01'
          description: 'Recognised as an emerging leader in the global metabolomics community by the American Chemical Society and Journal of Proteome Research.'
          icon: ''
          organization: American Chemical Society / Journal of Proteome Research
          organization_url: 'https://pubs.acs.org/journal/jprobs'
          title: 'Rising Stars in Proteomics and Metabolomics: 40 Under 40'
          url: ''
        - certificate_url: ''
          date_end: '2024-01-01'
          date_start: '2021-01-01'
          description: 'Nominated finalist in four consecutive years (2021, 2022, 2023, 2024).'
          icon: ''
          organization: Murdoch University
          organization_url: 'https://www.murdoch.edu.au'
          title: Vice-Chancellor Excellence in Research (Early Career) Award — Finalist
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2018-01-01'
          description: 'Competitive early career development award supporting research into dementia metabolomics.'
          icon: ''
          organization: Dementia Platforms UK
          organization_url: ''
          title: Early Career Development Award
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2018-01-01'
          description: 'EU educational travel award for excellence in mass spectrometry research.'
          icon: ''
          organization: MSACL
          organization_url: ''
          title: MSACL EU Educational Travel Award
          url: ''
    design:
      columns: '2'

  - block: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Senior Lecturer in Biochemistry
          company: Curtin University
          company_url: 'https://www.curtin.edu.au'
          company_logo: ''
          location: Perth, Western Australia
          date_start: '2025-01-01'
          date_end: ''
          description: |2-
              * Established independent research group within the Curtin Medical Research Institute
              * Teaching across undergraduate biochemistry programme
              * Dementia Australia Royce Simmons Foundation Mid-Career Research Fellow (2024–2026)

        - title: Senior Lecturer, Phenomics in Healthy Ageing and Dementia
          company: Murdoch University / Australian National Phenome Centre
          company_url: 'https://www.murdoch.edu.au/research/anpc'
          company_logo: ''
          location: Perth, Western Australia
          date_start: '2019-10-01'
          date_end: '2025-01-01'
          description: |2-
              * Commissioned and developed the Australian National Phenome Centre
              * Led metabolic phenotyping research in neurodegeneration, trauma, and infectious disease
              * Founded and delivered the Master of Research in Systems Medicine programme
              * Adjunct Senior Lecturer (2025–present)

        - title: Post-doctoral Research Associate
          company: Imperial College London (UK DRI / National Phenome Centre)
          company_url: 'https://www.imperial.ac.uk'
          company_logo: ''
          location: London, UK
          date_start: '2016-01-01'
          date_end: '2019-10-01'
          description: |2-
              * Developed mass spectrometry platforms for population-scale metabolic profiling at the MRC-NIHR National Phenome Centre
              * Investigated metabolic underpinnings of neurodegeneration at the UK Dementia Research Institute
              * Honorary Research Associate 2019–2021

        - title: Analytical Chemist
          company: Defence Science and Technology Laboratory
          company_url: ''
          company_logo: ''
          location: UK
          date_start: '2014-01-01'
          date_end: '2016-01-01'
          description: Mass spectrometry specialist for the UK Ministry of Defence.

        - title: Anti-doping Analyst
          company: Drug Control Centre, King's College London
          company_url: ''
          company_logo: ''
          location: London, UK
          date_start: '2012-01-01'
          date_end: '2014-01-01'
          description: Anti-doping analysis including at Olympic Games drug testing facility.
    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: ''
      email: luke.whiley@curtin.edu.au
      address:
        street: ''
        city: Perth
        region: Western Australia
        postcode: ''
        country: Australia
        country_code: AU
      contact_links:
        - icon: google-scholar
          icon_pack: ai
          name: Google Scholar
          link: 'https://scholar.google.com/citations?user=2qkN8C0AAAAJ&hl=en'
        - icon: linkedin
          icon_pack: fab
          name: LinkedIn
          link: 'https://www.linkedin.com/in/luke-whiley/'
        - icon: github
          icon_pack: fab
          name: GitHub
          link: 'https://github.com/lukewhiley'
      autolink: true
      form:
        provider: ''
    design:
      columns: '2'
---