---
title: 공연영상모음
summary: 제가 다닌 공연을 함께 봐요
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: teaching
    content:
      title: 콘서트
      filters:
        folders:
          - concert
    design:
      view: article-grid
      columns: 3
---