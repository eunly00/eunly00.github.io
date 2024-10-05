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
      title: "<span style='font-family: Arial, sans-serif; font-size: 36px; color: #3C6478;'>About Me</span>"
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
      title: "<span style='font-family: Arial, sans-serif; font-size: 28px; color: #3C6478;'>MY SKILLS</span>"
      item:
        - icon: python
          icon_pack: fab
          name: "<span style='font-family: Arial, sans-serif; font-size: 22px; color: #5A9EAE;'>Python</span>"
          description: "<span style='color: #647785;'>80%</span>"
        - icon: code
          icon_pack: fas
          name: "<span style='font-family: Arial, sans-serif; font-size: 22px; color: #5A9EAE;'>C/C++</span>"
          description: "<span style='color: #647785;'>100%</span>"
        - icon: database
          icon_pack: fas
          name: "<span style='font-family: Arial, sans-serif; font-size: 22px; color: #5A9EAE;'>SQL</span>"
          description: "<span style='color: #647785;'>40%</span>"

  - block: accomplishments  # list 블록으로 경력 표시
    id: experience
    content:
      title: "<span style='font-family: Arial, sans-serif; font-size: 28px; color: #3C6478;'>My Experience</span>"
      items:
        - title: 'sLLM으로 배우는 생성형 AI'
          organization: 한동대빅데이터캠프
          organization_url: 'https://www.coursera.org'
          date: '2018-10-01'
          description: 'Coursera에서 수강한 생성형 AI 강좌'
        - title: 'Blockchain Fundamentals'
          organization: 드론코딩경진대회
          organization_url: 'https://www.edx.org'
          date: '2018-03-01'
          description: 'Blockchain과 관련된 기본 개념을 배움'
        - title: 'Object-Oriented Programming in R: S3 and R6 Course'
          organization: 기업의달인되기
          organization_url: 'https://www.datacamp.com'
          date: '2017-07-01'
          description: 'Datacamp에서 R의 OOP를 배운 과정'

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
        - title: "<span style='font-family: Arial, sans-serif; font-size: 24px; color: #3C6478;'>👋 Welcome to the group</span>"
          content: "<span style='font-family: Arial, sans-serif; font-size: 18px; color: #647785;'>Take a look at what we're working on...</span>"
          align: center
          background:
            position: right
            color: '#666'
            brightness: 0.7
            media: '클라이밍.png'
            fit: cover
        - title: "<span style='font-family: Arial, sans-serif; font-size: 24px; color: #3C6478;'>Lunch & Learn ☕️</span>"
          content: "<span style='font-family: Arial, sans-serif; font-size: 18px; color: #647785;'>Share your knowledge with the group and explore exciting new topics together!</span>"
          align: left
          background:
            position: center
            color: '#555'
            brightness: 0.7
            media: '클라이밍2.png'
            fit: cover
        - title: "<span style='font-family: Arial, sans-serif; font-size: 24px; color: #3C6478;'>World-Class Semiconductor Lab</span>"
          content: "<span style='font-family: Arial, sans-serif; font-size: 18px; color: #647785;'>Just opened last month!</span>"
          align: right
          background:
            position: center
            color: '#333'
            brightness: 0.5
            media: '클라이밍3.png'
            fit: cover
          link:
            icon: graduation-cap
            icon_pack: fas
            text: Join Us
            url: ../contact/

  - block: collection
    id: papers
    content:
      title: "<span style='font-family: Arial, sans-serif; font-size: 28px; color: #3C6478;'>기업 인터뷰</span>"
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: "<span style='font-family: Arial, sans-serif; font-size: 28px; color: #3C6478;'>Recent Publications</span>"
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
      title: "<span style='font-family: Arial, sans-serif; font-size: 28px; color: #3C6478;'>Projects</span>"
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 3

---
