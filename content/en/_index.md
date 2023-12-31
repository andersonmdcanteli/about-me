---
date: "2023-12-24"

sections:

- block: about.biography
  content:
    title: Biography
    username: admin
  id: about


- block: skills
  content:
    text: ""
    title: Skills
    username: admin
  design:
    columns: "1"

    
- block: experience
  content:
    date_format: Jan 2006
    items:

    - company: Anderson Canteli Treinamento & Consultoria
      company_logo: actec
      company_url: "https://andersoncanteli.com.br/"
      date_start: "2020-12-01"
      date_end: ""
      description: |2-
          Responsibilities

          - Teach classes
          - Develop courses
          - Develop/record tutorials
          - Create dashboards for data analysis
          
      location: Curitiba
      title: Teacher

    - company: Federal University of Parana (UFPR)
      company_logo: ufpr
      company_url: ""
      date_start: "2014-03-01"
      date_end: "2018-03-01"
      description: |2-
          Development of the doctoral thesis

          *[Adsorção de corante por um biossorvente obtido do casulo do bicho-da-seda (Bombyx mori): experimentos e modelagem](https://acervodigital.ufpr.br/xmlui/handle/1884/58189)*
          
      location: Curitiba
      title: Master's student


    - company: Federal University of Parana (UFPR)
      company_logo: ufpr
      company_url: ""
      date_start: "2011-03-01"
      date_end: "2013-03-01"
      description: |2-
          Development of the master's thesis

          *[Recuperação do aroma de café, benzaldeído, em coluna de adsorção utilizando carvão ativado](https://acervodigital.ufpr.br/handle/1884/30536)*
          
      location: Curitiba
      title: Master's student


    title: Experience
  design:
    columns: "2"



- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://www.coursera.org
      date_end: ""
      date_start: "2021-01-25"
      description: ""
      icon: coursera
      organization: Coursera
      organization_url: https://www.coursera.org
      title: Neural Networks and Deep Learning
      url: ""
    - certificate_url: https://www.edx.org
      date_end: ""
      date_start: "2021-01-01"
      description: Formulated informed blockchain models, hypotheses, and use cases.
      icon: edx
      organization: edX
      organization_url: https://www.edx.org
      title: Blockchain Fundamentals
      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    - certificate_url: https://www.datacamp.com
      date_end: "2020-12-21"
      date_start: "2020-07-01"
      description: ""
      icon: datacamp
      organization: DataCamp
      organization_url: https://www.datacamp.com
      title: Object-Oriented Programming in R
      url: ""
    subtitle: null
    title: Accomplish&shy;ments
  design:
    columns: "2"
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
- block: contact
  content:
    address:
      city: Stanford
      country: United States
      country_code: US
      postcode: "94305"
      region: CA
      street: 450 Serra Mall
    appointment_url: https://calendly.com
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/Twitter
      name: DM Me
    - icon: skype
      icon_pack: fab
      link: skype:echo123?call
      name: Skype Me
    - icon: video
      icon_pack: fas
      link: https://zoom.com
      name: Zoom Me
    coordinates:
      latitude: "37.4275"
      longitude: "-122.1697"
    directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    email: test@example.org
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    office_hours:
    - Monday 10:00 to 13:00
    - Wednesday 09:00 to 10:00
    phone: 888 888 88 88
    subtitle: null
    text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
      ut magna et, vehicula efficitur enim.
    title: Contact
  design:
    columns: "2"
  id: contact
title: ""
type: landing
---
