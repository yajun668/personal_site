---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
  
- block: experience
  content:
    # Date format for experience
    # Refer to https://wowchemy.com/docs/customization/#date-format
    date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
    items:
    - company: Jacksonville State University, 
      company_logo: jsu
      company_url: "https://www.jsu.edu/"
      date_end: ""
      date_start: "2021-08-02"
      location: Jacksonville, AL, USA
      title: Assistant Professor of Analytics & Operations Management
    - company: Bucknell University
      company_logo: bucknell
      company_url: "https://www.bucknell.edu/"
      date_end: "2021-05-31"
      date_start: "2019-08-01"
      location: Lewisburg, PA, USA
      title: Visiting Assistant Professor of Business Analytics
    - company: Huawei Technologies Co., Ltd.
      company_logo: huawei
      company_url: "https://www.huawei.com/en"
      date_end: "2014-07-15"
      date_start: "2011-03-11"
      description: Job Duty -- Optimization and Simulation, Data Analytics, Supply Chain Management, Lean Manufacturing
      location: Shenzhen, China
      title: Industrial Engineer
    title: Experience
  design:
    columns: "2"

  
- block: collection
  content:
    # Choose how many pages you would like to display (0 = all pages)
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - posts
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Posts
  design:
    columns: "2"
    view: compact
  id: posts

- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Jacksonville State University
      tag: JSU
    - name: Bucknell University
      tag: Bucknell
    - name: Oklahoma State University
      tag: OSU
    default_button_index: 0
    filters:
      folders:
      - project
    title: Teaching
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
  
  
- block: collection
  id: publication
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
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
title: null
type: landing
---

