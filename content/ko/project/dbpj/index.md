---
title: '데이터베이스 팀 프로젝트 : 전북대 주변 맛집 추천 서비스'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 임성혁
  - 조대인
  - 최홍석

date: '2024-06-10T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-06T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: 장재우 교수님의 데이터베이스 수업에서 진행한 프로젝트 과제입니다.

# Summary. An optional shortened abstract.
summary: 데이터베이스 팀 프로젝트 활동

tags: [데이터베이스, SQL, 추천]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/highcastle01/path_recom_db_pj'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

## 캡스톤 ##

### AI 기반 감정일기 ###

졸업을 앞둔 혹은 졸업을 할 생각이 있는 전북대학교 컴퓨터인공지능학부생은 무조건 거쳐야만 하는 것이 바로 캡스톤이다.
이 캡스톤을 4학년도 아닌 3학년에 하게 되면서 꽤나 많은 고민이 되었다.

### 데이터 전처리 ###

Ai hub에서 제공되는 정제된 데이터나 각종 인터넷 커뮤니티의 게시글들을 크롤링한 뒤 가공, 전처리 하였다.

### 프론트엔드 ###

앱으로 개발하기 위해 React Native로 제작 하였다.

### 백엔드 ###

미들웨어를 비롯한 각종 모듈들을 쉽게 다루기 위해 Nest.js를 사용하였고, Postgresql을 사용하였다.

### LLM ###

Kobert 모델을 통해 감정을 분류하고
Llama3 모델을 이용해 메세지를 생성하여 제공하였다.
