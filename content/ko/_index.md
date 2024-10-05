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
          filename: sky.png
          size: cover
          position: center
          parallax: true
          overlay:  # 이미지 위에 투명도 레이어 적용
            color: '#000000'  # 검정색
            opacity: 0.7      # 70% 투명도
      container:  # 컨테이너 크기 조절
        width: 70%  # 너비를 70%로 설정
        max-width: 1200px  # 최대 너비를 1200px로 설정
        padding: 20px  # 내부 여백 조정
        margin: 0 auto  # 가운데 정렬
    text_overlay:  # 텍스트 오버레이
      align: center
      color: '#ffffff'  # 흰색 텍스트

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

      - title: <span style="font-size:90%">TREC2024 참여</span>
        content: <span style="font-size:90%">이번 여름에 참여한 TREC2024<span style="font-size:90%">
        align: center
        background:
          image:
            filename: trec1.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: 게시글
          url: ../activity/lab/trec2024

      - title: <span style="font-size:90%">전북대 대동제</span>
        content: <span style="font-size:90%">잔나비 공연</span>
        align: right
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: 영상시청
          url: ../hobbies/concert/jannabi

    design:
      slide_height: '350px'
      slide_width: '100%'
      is_fullscreen: false
      loop: true
      interval: 3000
---
