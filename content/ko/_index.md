---
# Leave the homepage title empty to use the site title
title: 사이트
date: 2022-10-24
type: landing

sections:

  - block: about.biography
    id: about
    content:
      title: ''
      username: 임성혁
    design:
      background:
        image:
          filename: jbnu1.png
          size: cover
          position: center
          parallax: true
          overlay:  # 이미지 위에 투명도 레이어 적용
            color: '#000000'  #검정색
            opacity: 0.5      #50% 투명도
    text_overlay:  #텍스트 오버레이
      align: center
      color: '#ffffff'  #흰색 텍스트

  - block: markdown
    content:
      title: '📚 활동 모음'
      subtitle: ''
      text: |-
        안녕하세요. 아래는 제가 대학시절 동안 활동한 내역들 입니다.
        부족하기도 하지만 열심히 한 작품들과 프로젝트들이니 보는 재미가 있을 겁니다.
        와주셔서 감사합니다.
    design:
      columns: '1'

  - block: slider
    content:
      slides:

      - title: <span style="font-size:90%">테스원</span>
        content: <span style="font-size:90%">테스트1<span style="font-size:90%">
        align: center
        background:
          image:
            filename: jbnu1.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">테스투</span>
        content: <span style="font-size:90%">테스트2</span>
        align: center
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

  - block: hero
    content:
      title: |
        Wowchemy
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
