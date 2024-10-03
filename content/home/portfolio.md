---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://docs.hugoblox.com/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: ''
subtitle: ''

sections:
  - block: slider
    content:
      slides:
      - title: AI
        content: AI을 이용한 웹서비스
        align: center
        background:
          image:
            filename: AI.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: C++
        content: C++ 마스터하기
        align: left
        background:
          image:
            filename: C.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Welcome
        content: 전북대학교 CSAI
        align: right
        background:
          image:
            filename: csai.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: 오시는 길
          url: ../about/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---

