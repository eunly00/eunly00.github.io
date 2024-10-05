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
      title: "<span style='font-size:75%'>MY SKILLS</span>"
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
        - icon: js
          icon_pack: fab
          name: JavaScript
          description: 70%
        - icon: html5
          icon_pack: fab
          name: HTML5
          description: 90%
        - icon: css3-alt
          icon_pack: fab
          name: CSS3
          description: 85%
        - icon: react
          icon_pack: fab
          name: React.js
          description: 60%
        - icon: github
          icon_pack: fab
          name: GitHub
          description: 75%

---