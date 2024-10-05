---
# Leave the homepage title empty to use the site title
title: "Eunsong's Profile"
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
      text: 'I am passionate about the following research and development areas:<br><br><br><br>'
      items:
        - name: Embedded Systems
          icon: microchip
          icon_pack: fas
          description: '<span style="font-size:90%">Design and development of real-time systems and embedded systems for IoT devices.</span><br><br>'
        - name: Internet of Things (IoT)
          icon: wifi
          icon_pack: fas
          description: '<span style="font-size:90%">Development of smart devices through IoT networks and sensor communication.</span><br><br>'
        - name: Information Security
          icon: lock
          icon_pack: fas
          description: '<span style="font-size:90%">Development of information security solutions including data security, network security, and encryption technologies.</span><br><br>'
        - name: Artificial Intelligence (AI)
          icon: brain
          icon_pack: fas
          description: '<span style="font-size:90%">Intelligent analysis of IoT devices and security systems using AI.</span><br><br>'
        - name: Cloud Computing
          icon: cloud
          icon_pack: fas
          description: '<span style="font-size:90%">Cloud-based infrastructure design for embedded systems and IoT.</span><br><br>'
        - name: Network Security
          icon: shield-alt
          icon_pack: fas
          description: '<span style="font-size:90%">Design of network security protocols for IoT and embedded devices.</span><br><br>'

  - block: features
    id: language_skills
    content:
      title: '<span style="font-size:75%">Language Skills</span>'
      text: 'Key programming languages and technology stacks:<br><br><br><br>'
      items:
        - name: Python
          icon: python
          icon_pack: fab
          description: '<span style="font-size:90%">Python for data science, AI, and web development.</span><br><br>'
        - name: JavaScript
          icon: js
          icon_pack: fab
          description: '<span style="font-size:90%">JavaScript for web and server-side development.</span><br><br>'
        - name: C++
          icon: cpanel
          icon_pack: fab
          description: '<span style="font-size:90%">C++ for developing high-performance applications and systems.</span><br><br>'
        - name: HTML5
          icon: html5
          icon_pack: fab
          description: '<span style="font-size:90%">HTML5 for structuring web pages.</span><br><br>'
        - name: CSS3
          icon: css3-alt
          icon_pack: fab
          description: '<span style="font-size:90%">CSS3 for styling web pages.</span><br><br>'
        - name: SQL
          icon: database
          icon_pack: fas
          description: '<span style="font-size:90%">SQL for managing databases.</span><br><br>'
---
