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
      title: "<span style='font-family: Arial, sans-serif; font-size: 36px;'>About Me</span>"
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
    content:
      title: "<span style='font-family: Arial, sans-serif; font-size: 28px;'>MY SKILLS</span>"
      item:
        - icon: python
          icon_pack: fab
          name: "<span style='font-family: Arial, sans-serif; font-size: 22px;'>Python</span>"
          description: 80%
        - icon: code
          icon_pack: fas
          name: "<span style='font-family: Arial, sans-serif; font-size: 22px;'>C/C++</span>"
          description: 100%
        - icon: database
          icon_pack: fas
          name: "<span style='font-family: Arial, sans-serif; font-size: 22px;'>SQL</span>"
          description: 40%

  - block: accomplishments  # Accomplishments widget section 추가
    content:
      title: "<span style='font-family: Arial, sans-serif; font-size: 28px;'>My Experience</span>"
      date_format: Jan 2006
      item:
        - organization: 한동대빅데이터캠프
          organization_url: 'https://www.coursera.org'
          title: "<span style='font-family: Arial, sans-serif; font-size: 22px;'>sLLM으로 배우는 생성형 AI</span>"
          url: ''
          certificate_url: 'https://www.coursera.org'
          date_start: '2018-10-01'
          date_end: ''
          description: ''
        - organization: 드론코딩경진대회
          organization_url: 'https://www.edx.org'
          title: "<span style='font-family: Arial, sans-serif; font-size: 22px;'>Blockchain Fundamentals</span>"
          url: >-
            https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals      
          certificate_url: 'https://www.edx.org'
          date_start: '2018-03-01'
          date_end: ''
          description: 'Formulated informed blockchain models, hypotheses, and use cases.'
        - organization: 기업의달인되기
          organization_url: 'https://www.datacamp.com'
          title: "<span style='font-family: Arial, sans-serif; font-size: 22px;'>Object-Oriented Programming in R: S3 and R6 Course</span>"
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
        - title: "<span style='font-family: Arial, sans-serif; font-size: 24px;'>👋 Welcome to the group</span>"
          content: "<span style='font-family: Arial, sans-serif; font-size: 18px;'>Take a look at what we're working on...</span>"
          align: center
          background:
            position: right
            color: '#666'
            brightness: 0.7
            media: 클라이밍.png
            fit: cover
        - title: "<span style='font-family: Arial, sans-serif; font-size: 24px;'>Lunch & Learn ☕️</span>"
          content: "<span style='font-family: Arial, sans-serif; font-size: 18px;'>Share your knowledge with the group and explore exciting new topics together!</span>"
          align: left
          background:
            position: center
            color: '#555'
            brightness: 0.7
            media: 클라이밍2.png
            fit: cover
        - title: "<span style='font-family: Arial, sans-serif; font-size: 24px;'>World-Class Semiconductor Lab</span>"
          content: "<span style='font-family: Arial, sans-serif; font-size: 18px;'>Just opened last month!</span>"
          align: right
          background:
            position: center
            color: '#333'
            brightness: 0.5
            media: 클라이밍3.png
            fit: cover
          link:
            icon: graduation-cap
            icon_pack: fas
            text: Join Us
            url: ../contact/

  - block: collection
    id: papers
    content:
      title: "<span style='font-family: Arial, sans-serif; font-size: 28px;'>기업 인터뷰</span>"
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: "<span style='font-family: Arial, sans-serif; font-size: 28px;'>Recent Publications</span>"
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
      title: "<span style='font-family: Arial, sans-serif; font-size: 28px;'>Projects</span>"
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 3

---
