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
    - company: Jacksonville State University
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
      description: "Job Duty: Optimization and Simulation, Data Analytics, Supply Chain Management,       Lean Manufacturing"  
      location: Shenzhen, China
      title: Industrial Engineer
    title: Experience
  design:
    columns: "2"
  id: experience


- block: collection
  id: publication
  content:
  # Choose how many pages you would like to display (0 = all pages)
    count: 4
    filters:
      exclude_featured: true
      folders:
      - publication
    title: Recent Publications
  design:
    columns: "2"
    view: citation  


- block: portfolio
  content:
    # Choose how many pages you would like to display (0 = all pages)
    count: 3
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
      - teaching
    title: Teaching
  design:
    columns: "2"
    view: compact
    # For Showcase view, flip alternate rows?
    flip_alt_rows: false
  id: teaching
  
# - block: collection
#   content:
#     # Choose how many pages you would like to display (0 = all pages)
#     count: 3
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       folders:
#       - news
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     subtitle: ""
#     text: ""
#     title: News
#   design:
#     columns: "2"
#     view: compact
#   id: news

# - block: collection
#   content:
#     # Choose how many pages you would like to display (0 = all pages)
#     count: 5
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       folders:
#       - posts
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     subtitle: ""
#     text: ""
#     title: Posts
#   design:
#     columns: "2"
#     view: compact
#   id: posts

- block: contact
  content:
    title: Contact
    phone: (256) 782-5398
    address:
      city: Jacksonville
      country: United States
      country_code: US
      postcode: "36265"
      region: AL
      street: 287 Merrill Hall, Jacksonville State University
    email: ylu[at]jsu.edu
    # Coordinates to display a map - set your map provider in `params.yaml`
    # coordinates:
    #   latitude: '33.8286517'
    #   longitude: '-85.7656348'
  design:
    columns: "2"
  id: contact
title: null
type: landing
---

