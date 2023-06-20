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
      - title: The PAIR Lab 
        content: decision making, strategic interaction, and AI-human alignment
        align: center
        background:
          image:
            filename: welcome2.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
      - title: " Safe Value Alignment for LLM"
        content: '智源大会：AI安全与对齐论坛'
        align: center
        background:
          image:
            filename: baai.png
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Talks
          url: ./talks/23-06-10-baai/
      - title: "基于大语言模型的开放世界智能决策"
        content: "RLChina 2023 专题报告"
        align: center
        background:
          image:
            filename: rlchina.png
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Talks
          url: ../talks/
      - title: "一个合作博弈的通用求解框架"
        content: "TechBeat 2022年度最受欢迎讲者"
        align: center
        background:
          image:
            filename: cop.png
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Talks
          url: ../talks/
      - title: "一个通用零和博弈的求解框架"
        content: "TechBeat 2021年度最受欢迎讲者"
        align: center
        background:
          image:
            filename: zero.png
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Talks
          url: ../talks/
      - title: "China XYZ: Artificial intelligence"
        content: 国务院新闻办中国网China.org
        align: center
        background:
          image:
            filename: china_org.png
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Interview
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3500
  - block: hero
    content:
      title: |
        Our Mission
      image:
        filename: welcome.jpg
      text: |
        <br>

        <font size=4.5>At the PKU Alignment and Interaction Research Lab (PAIR Lab), we address the fundamental challenges in decision-making, strategic interactions, and value alignment towards achieving artificial general intelligence (AGI). Our expertise encompasses **reinforcement learning** for refined decision-making, **multi-agent systems and game theory** for complex    strategic interactions, and **RLHF** techniques for secure AGI-human value alignment. Our integrative methodology aims to guide AGI development towards a safe, beneficial future in synchrony with humanity and eternal prosperity of mankind.</font>
  
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
