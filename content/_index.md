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
        content: decision making, strategic interaction, and human-AI alignment
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
      - title: "Safe Value Alignment for LLMs"
        content: '智源大会：AI安全与对齐论坛'
        align: center
        background:
          image:
            filename: align.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Talks
          url: https://www.bilibili.com/video/BV1gh411T7qS
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
          url: https://www.bilibili.com/video/BV1hg4y1x7iT
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
          url: https://www.techbeat.net/talk-info?id=715
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
          url: https://www.techbeat.net/talk-info?id=501
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
          url: http://mp42.china.com.cn/video_tide/video/2023/5/30/20235301685434452218_369_3.mp4
      - title: "主题节目：新征程上科教兴国还需人才支撑"
        content: 央视一套《焦点访谈》
        align: center
        background:
          image:
            filename: jiaodian.png
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Interview
          url: https://tv.cctv.com/2022/11/25/VIDEUpzcpDMv6qH5hivGIGqH221125.shtml
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2500
  - block: hero
    content:
      title: |
        Our Mission
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        <font size=4.5>The PKU Alignment and Interaction Research Lab (PAIR Lab) is dedicated to addressing key challenges in decision making, strategic interactions, and value alignment for artificial general intelligence (AGI). We specialize in reinforcement learning for intelligent **decisions**, multi-agent systems for complex strategic **interactions**, and **alignment** techniques for harmonizing AGI with human values and intentions. Our integrative approach aims to steer AGI development towards a safe, beneficial future aligned with the progression of humanity. Our research focus includes: </font>
        <font size=3.8>
        - **Reinforcement Learning**: safe RL, MARL, meta RL, offline RL, PbRL
        - **Game Theory**: solution concepts, game decomposition, meta-game analysis
        - **Alignment**: RLHF, multi-agent alginment, self-alignment, constitutional AI
        
        </font>
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
