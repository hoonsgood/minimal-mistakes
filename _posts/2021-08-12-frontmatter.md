---
layout: single

title: 'Front Matter 설정하기'
excerpt: '발췌부분 설정하면 이 글이 들어가고, 설정하지 않는다면 글의 첫 문단이 들어가게됨'

date: 2021-08-12 20:17:00 +0900
lastmod: 2021-08-12 20:17:00 +0900 # sitemap.xml에서 사용됨

author_profile: false # 왼쪽부분 프로필을 띄울건지

header:
  overlay_image: https://images.unsplash.com/photo-1501785888041-af3ef285b470?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80
  overlay_filter: 0.5 # 투명도

categories:
  - SW

tags:
  - github.io

# table of contents
toc: true # 오른쪽 부분에 목차를 자동 생성해준다.
toc_label: 'table of content' # toc 이름 설정
toc_icon: 'bars' # 아이콘 설정
toc_sticky: true # 마우스 스크롤과 함께 내려갈 것인지 설정
---

## Front Matter 설정하기

GitHub Pages에 글을 올리기 위해 post파일을 만들 때, Front Matter 설정을 통해 블로그를 더 편하게 사용할 수 있게한다.

```
layout: single

title: "Front Matter 설정하기"
excerpt: "발췌부분 설정하면 이 글이 들어가고, 설정하지 않는다면 글의 첫 문단이 들어가게됨"

date: 2021-08-12 20:17:00 +0900
lastmod: 2021-08-12 20:17:00 +0900 # sitemap.xml에서 사용됨

author_profile: false # 왼쪽부분 프로필을 띄울건지

header:
  overlay_image: https://images.unsplash.com/photo-1501785888041-af3ef285b470?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80
  overlay_filter: 0.5 # 투명도

categories:
  - github io

tags:
    - github io
    - theme
    - front matter

# table of contents
toc: true # 오른쪽 부분에 목차를 자동 생성해준다.
toc_label: "table of content" # toc 이름 설정
toc_icon: "bars" # 아이콘 설정
toc_sticky: true # 마우스 스크롤과 함께 내려갈 것인지 설정
```
