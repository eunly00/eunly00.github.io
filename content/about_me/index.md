---
# Leave the homepage title empty to use the site title
title: "About Me"
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

---