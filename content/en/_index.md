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

      - title: <span style="font-size:70%">Embedded Systems</span>
        content: <span style="font-size:70%">Design and development of real-time systems and embedded systems for IoT devices</span>
        align: center
        background:
          image:
            filename: embedded.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Internet of Things (IoT)</span>
        content: <span style="font-size:70%">Development of smart devices through IoT networks and sensor communications</span>
        align: center
        background:
          image:
            filename: IoT.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Information Security</span>
        content: <span style="font-size:70%">Development of information security solutions such as data security, network security, and encryption technology</span>
        align: center
        background:
          image:
            filename: security.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Artificial Intelligence (AI)</span>
        content: <span style="font-size:70%">Intelligent analysis of IoT devices and security systems using AI</span>
        align: center
        background:
          image:
            filename: AI.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Cloud Computing</span>
        content: <span style="font-size:70%">Cloud-based infrastructure design for embedded systems and IoT</span>
        align: center
        background:
          image:
            filename: cloud.png
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
      title: Company Interviews
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
