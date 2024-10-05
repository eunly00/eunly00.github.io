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
    
          
  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">임베디드 시스템 (Embedded Systems)</span>
        content: <span style="font-size:70%">실시간 시스템 설계 및 개발, IoT 장치의 내장 시스템 개발</span>
        align: center
        background:
          image:
            filename: 임베디드.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">사물인터넷 (IoT)</span>
        content: <span style="font-size:70%">IoT 네트워크 및 센서 통신을 통한 스마트 디바이스 개발<span style="font-size:70%">
        align: center
        background:
          image:
            filename: IoT.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">정보보안 (Information Security)</span>
        content: <span style="font-size:70%">데이터 보안, 네트워크 보안, 암호화 기술 등 정보보안 솔루션 개발</span>
        align: center
        background:
          image:
            filename: 정보보안.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">인공지능 (AI)</span>
        content: <span style="font-size:70%">AI를 활용한 IoT 기기와 보안 시스템의 지능형 분석</span>
        align: center
        background:
          image:
            filename: 인공지능.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">클라우드 컴퓨팅 (Cloud Computing)</span>
        content: <span style="font-size:70%">임베디드 시스템과 IoT를 위한 클라우드 기반 인프라 설계</span>
        align: center
        background:
          image:
            filename: 클라우딩.png
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
      title: 기업인터뷰
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: community/custom_card
      columns: '2'
    advanced:
      css_style: "text-align: center;"


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