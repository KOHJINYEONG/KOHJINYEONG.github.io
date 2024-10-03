---
# Use the Intro widget of the Blog template
widget: about.avatar

# This file represents a page section.
headless: true

# Order that this section will appear in.
weight: 10

author: admin
#design:
#  background:
#    color: '#090a0b'
#    text_color_light: true
#    video:
#      path:  # enter filename of a video in /assets/media
#  css_class: fullscreen

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
            color: "#666"
        - title: C++
          content: C++ 마스터하기
          align: left
          background:
            image:
              filename: C.jpg
              filters:
                brightness: 0.7
            position: center
            color: "#555"
        - title: Welcome
          content: 전북대학교 CSAI
          align: right
          background:
            image:
              filename: csai.jpg
              filters:
                brightness: 0.5
            position: center
            color: "#333"
          link:
            icon: graduation-cap
            icon_pack: fas
            text: 오시는 길
            url: ../about/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ""
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
      columns: "1"
---

😊 안녕하세요 전북대학교 IT지능정보공학과 3학년 재학중인 고진영입니다.
{style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"}

저의 홈페이지에 오신 것을 환영합니다.
