---
# Leave the homepage title empty to use the site title
title: "EUNSONG's History"
date: 2024-09-22
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: features
    content:
      # User profile display (replacing content from `admin/_index.md`)
      title: 박 은 송
      name_pronunciation: PARK EUN SONG
      first_name: EUN SONG
      last_name: PARK
      status:
        icon: ☕️
      superuser: true
      highlight_name: true
      profiles:
        - icon: at-symbol
          url: 'mailto:songr0821@gmail.com'
          label: E-mail Me
        - icon: brands/instagram
          url: https://www.instagram.com/10.26.rio?igsh=MW51N25hcWE3YXplcw%3D%3D&utm_source=qr
        - icon: brands/github
          url: https://github.com/gcushen
      interests:
        - 임베디드 시스템
        - IoT
        - 정보보안
      education:
        - area: 컴퓨터공학부
          institution: 전북대학교
          date_start: 2022-03-01
          button:
            text: '재학증명서/성적표'
            url: 'https://example.com'
      skills:
        - name: Technical Skills
          items:
            - name: Python
              description: ''
              percent: 80
              icon: code-bracket
            - name: C/C++
              description: ''
              percent: 100
              icon: chart-bar
            - name: SQL
              description: ''
              percent: 40
              icon: circle-stack
      button:
        text: 이력서 다운로드하기
        url: uploads/cv.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: Slight Ocean View.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

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

