---
# Leave the homepage title empty to use the site title
title: "EUNSONG's History"
date: 2024-09-22
type: landing

design:
  # Default section spacing
  spacing: "6rem"


sections:
  - block: about.biography
    id: about
    content:
      title: ""
      username: admin
    design:
      background:
        image:
          filename: Slight Ocean View.jpg
          # Optional: Set background image options
          size: cover
          position: center
          parallax: false



  - block: features  # Feature widget section 추가
    id: features
    weight: 10
    content:
      title: <span style="font-size:75%">Lab's Interests</span>
      text: MY SKILLS.<br><br><br><br>
      items:
        - icon: python
          icon_pack: fab
          name: Python
          description: 80%
        - icon: code
          icon_pack: fas
          name: C/C++
          description: 100%
        - icon: database
          icon_pack: fas
          name: SQL
          description: 40%

  - block: accomplishments  # Accomplishments widget section 추가
    widget: accomplishments
    weight: 20
    headless: true
    content:
      title: My Experience
      date_format: Jan 2006
      item:
        - organization: 한동대빅데이터캠프
          organization_url: 'https://www.coursera.org'
          title: sLLM으로 배우는 생성형 AI
          url: ''
          certificate_url: 'https://www.coursera.org'
          date_start: '2018-10-01'
          date_end: ''
          description: ''
        - organization: 드론코딩경진대회
          organization_url: 'https://www.edx.org'
          title: Blockchain Fundamentals
          url: >-
            https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals      
          certificate_url: 'https://www.edx.org'
          date_start: '2018-03-01'
          date_end: ''
          description: 'Formulated informed blockchain models, hypotheses, and use cases.'
        - organization: 기업의달인되기
          organization_url: 'https://www.datacamp.com'
          title: 'Object-Oriented Programming in R: S3 and R6 Course'
          url: ''
          certificate_url: 'https://www.datacamp.com'
          date_start: '2017-07-01'
          date_end: '2017-12-21'
          description: ''

          
  - block: slider  # 슬라이더 블록 추가
    widget: slider
    weight: 1
    active: true
    headless: true
    design:
      slide_height: '400px'  # 슬라이더의 높이를 400px로 설정
      is_fullscreen: false
      loop: true  # 슬라이더가 자동으로 루프
      interval: 3000  # 슬라이드 전환 간격 (3초)
    content:
      slides:
        - title: 👋 Welcome to the group
          content: Take a look at what we're working on...
          align: center
          background:
            position: right
            color: '#666'
            brightness: 0.7
            media: 히말라야2.jpg
            fit: cover
        - title: Lunch & Learn ☕️
          content: 'Share your knowledge with the group and explore exciting new topics together!'
          align: left
          background:
            position: center
            color: '#555'
            brightness: 0.7
            media: 히말라야2.jpg
            fit: cover
        - title: World-Class Semiconductor Lab
          content: 'Just opened last month!'
          align: right
          background:
            position: center
            color: '#333'
            brightness: 0.5
            media: 히말라야2.jpg
            fit: cover
          link:
            icon: graduation-cap
            icon_pack: fas
            text: Join Us
            url: ../contact/
  - block: collection
    id: papers
    content:
      title: 기업 인터뷰
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: interest
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 3

---

