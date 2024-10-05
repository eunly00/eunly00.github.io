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
    content:
      title:  <span style="font-size:75%">MY SKILLS</span>
      item:
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
          
          
  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Recruit</span>
        content: <span style="font-size:70%">Interested in MacsLAB?</span>
        align: center
        background:
          image:
            filename: 클라이밍.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Join Us</span>
          text-color: '#000'
          url: contact

      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:70%">의료/항공우주/컨텐츠 등 특성화 분야에 적용 가능한 AI 기술 개발<span style="font-size:70%">
        align: center
        background:
          image:
            filename: 클라이밍2.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Healthcare</span>
        content: <span style="font-size:70%">의료 및 헬스케어 분야에 적용 가능한 AI 기술 개발</span>
        align: center
        background:
          image:
            filename: 클라이밍3.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Mathematics</span>
        content: <span style="font-size:70%">AI와 관련된 수학 및 최적화 이론 연구</span>
        align: center
        background:
          image:
            filename: 클라이밍4.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">기반 기술을 활용한 Full-Stack 어플리케이션 개발</span>
        align: center
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  - block: collection
    content:
      title: 기업 인터뷰
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: grid
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