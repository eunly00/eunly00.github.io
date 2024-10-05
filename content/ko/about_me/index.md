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

  - block: features
    id: research_interests
    content:
      title: '<span style="font-size:75%">Research Interests</span>'
      text: '저는 다음과 같은 연구/개발 분야에 관심을 쏟고 있습니다.<br><br><br><br>'
      items:
        - name: 임베디드 시스템 (Embedded Systems)
          icon: microchip
          icon_pack: fas
          description: '<span style="font-size:90%">실시간 시스템 설계 및 개발, IoT 장치의 내장 시스템 개발.</span><br><br>'
        - name: 사물인터넷 (IoT)
          icon: wifi
          icon_pack: fas
          description: '<span style="font-size:90%">IoT 네트워크 및 센서 통신을 통한 스마트 디바이스 개발.</span><br><br>'
        - name: 정보보안 (Information Security)
          icon: lock
          icon_pack: fas
          description: '<span style="font-size:90%">데이터 보안, 네트워크 보안, 암호화 기술 등 정보보안 솔루션 개발.</span><br><br>'
        - name: 인공지능 (AI)
          icon: brain
          icon_pack: fas
          description: '<span style="font-size:90%">AI를 활용한 IoT 기기와 보안 시스템의 지능형 분석.</span><br><br>'
        - name: 클라우드 컴퓨팅 (Cloud Computing)
          icon: cloud
          icon_pack: fas
          description: '<span style="font-size:90%">임베디드 시스템과 IoT를 위한 클라우드 기반 인프라 설계.</span><br><br>'
        - name: 네트워크 보안 (Network Security)
          icon: shield-alt
          icon_pack: fas
          description: '<span style="font-size:90%">IoT 및 임베디드 장치의 네트워크 보안 프로토콜 설계.</span><br><br>'

  - block: features
    id: language_skills
    content:
      title: '<span style="font-size:75%">Language Skills</span>'
      text: '주요 프로그래밍 언어 및 기술 스택:<br><br><br><br>'
      items:
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
