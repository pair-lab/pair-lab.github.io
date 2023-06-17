---
# Leave the homepage title empty to use the site title
title:
date: 2023-06-17
type: landing

sections:
  - block: slider
    
    design:
      loop: true
      interval: 10
    content:
      slides:
      # - title: PAIR Lab
      #   content: Take a look at what we're working on...
      #   align: center
      #   background:
      #     image:
      #       filename: welcome.jpg
      #       filters:
      #         brightness: 0.7
      #     position: right
      #     color: '#666'
      #   link:
      #     icon: graduation-cap
      #     icon_pack: fas
      #     text: Recent News
      #     url: ../talks/
      - title: "BAAI2023: Safe Value Alignment for LLM"
        content: 'AI安全与对齐论坛'
        align: center
        background:
          image:
            filename: baai.png
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: PKU-Alignment Team
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
  - block: hero
    content:
      title: |
        PAIR Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        At the PKU Alignment and Interaction Research Lab (PAIR Lab), we address the fundamental challenges in decision-making, strategic interactions, and value alignment within AGI. Our expertise encompasses reinforcement learning for refined decision-making, multi-agent systems and game theory for complex interactions, and RLHF techniques for secure AGI-human value alignment. Our integrative methodology aims to guide AGI development towards a safe, beneficial future in synchrony with humanity.
  
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
