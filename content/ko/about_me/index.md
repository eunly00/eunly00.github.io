---
# Leave the homepage title empty to use the site title
title: "은송의 프로필"
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

  - block: features  # 여기에 들여쓰기를 맞춰줍니다.
    id: features
    content:
       title: <span style="font-size:75%">Lab's Interests</span> 
       text: '저희 연구실에서는 다음과 같은 연구/개발 분야에 관심을 쏟고 있습니다.<br><br><br><br>'
       items:
        - name: 인공지능(AI)
          icon: code-branch
          icon_pack: fas
          description: '<span style="font-size:90%">의료 (Medical), 항공우주 (Aerospace), 컨텐츠 (Contents) 등 다양한 특성화 분야에 적응형 AI 기술 적용.</span><br><br>'
        - name: 멀티모달(Multi-modality)
          icon: globe
          icon_pack: fas
          description:  '<span style="font-size:90%">Vision & Language 분야의 기반 AI 기술 개발 및 관련 응용 어플리케이션에 기술 적용.</span><br><br>'
        - name: 의료수학(Medical Math)
          icon: calculator
          icon_pack: fas
          description:  '<span style="font-size:90%">의료 분야에 대한 통계 분석 수행 및 의료 질병에 대한 수학적인 모델링 관련 연구 수행.</span><br><br>'
        - name: 컨텐츠 (Contents)
          icon: comment-dots
          icon_pack: fas
          description:  '<span style="font-size:90%">웹툰 및 미디어 컨텐츠와 관련된 AI 기반 기술 개발 및 고도화.</span><br><br>'
        - name: 개발 (Development)
          icon: laptop
          icon_pack: fas
          description:  '<span style="font-size:90%">Full-Stack 기반의 응용 어플리케이션 개발.</span><br><br>'
        - name: 솔루션 (Solution)
          icon: app-store-ios
          icon_pack: fab
          description:  '<span style="font-size:90%">AI 기반기술 및 관련 어플리케이션에 적용을 통한 통합 솔루션 개발!</span><br><br>'
        - name: Python
          icon: python
          icon_pack: fab
          description: '<span style="font-size:90%">데이터 과학, AI 및 웹 개발을 위한 파이썬.</span><br><br>'
        - name: JavaScript
          icon: js
          icon_pack: fab
          description: '<span style="font-size:90%">웹 및 서버 사이드 개발을 위한 자바스크립트.</span><br><br>'
        - name: C++
          icon: cpanel
          icon_pack: fab
          description: '<span style="font-size:90%">고성능 응용 프로그램과 시스템 개발에 사용되는 C++.</span><br><br>'
        - name: HTML5
          icon: html5
          icon_pack: fab
          description: '<span style="font-size:90%">웹 페이지 구조화를 위한 HTML5.</span><br><br>'
        - name: CSS3
          icon: css3-alt
          icon_pack: fab
          description: '<span style="font-size:90%">웹 페이지 스타일링을 위한 CSS3.</span><br><br>'
        - name: SQL
          icon: database
          icon_pack: fas
          description: '<span style="font-size:90%">데이터베이스 관리를 위한 SQL.</span><br><br>'
---
