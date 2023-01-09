---
layout: post
title: "Github 블로그 게시물 업로드 방법 및 마크다운 문법"
summary: "Multi Author Support allows to create articles with different Authors"
author: joon
date: "2022-01-09 22:35:23 +0530"
category: joon
thumbnail: /assets/img/posts/code.jpg
keywords: devlopr jekyll, how to use devlopr, devlopr, how to use devlopr-jekyll, devlopr-jekyll tutorial,best jekyll themes, multi author
usemathjax: true
permalink: /blog/Github 블로그 게시물 업로드 방법 및 마크다운 문법/
---

# Github 블로그 게시물 업로드 방법 및 마크다운 문법

## 🎉목차

- 게시물 작성 및 올리는 방법
- 자주 사용할 마크다운 문법

### 게시물 작성 및 올리는 방법

1. '\_post 폴더'에 게시물이름.md 파일 생성

2. 게시물 상단에 다음과 같이 yml 형식 제목 및 게시물 정보 작성

'''yml

---

layout: post
title: "Github 블로그 첫 게시물 올리기 테스트 및 올리는 법"
author: joon
date: "2022-01-09 21:30"
category: test
thumbnail: /assets/img/posts/code.jpg
usemathjax: false
permalink: /blog/test/

---

'''

3. 게시물 작성 후 파일 저장

4. git add -> git commit -> git push

```
git add .
git commit -m "20220109 Github 블로그 게시물 업로드 방법 및 마크다운 문법"
git push -u origin master
```

### 자주 사용할 마크다운 문법

수 많은 마크다운 문법이 존재하지만, 여기서는 제가 자주 사용할 거 같은 문법만 따로 정리하였습니다.

1. Header

글의 제목이 되며 각 제목마다 permalink가 존재한다.
\# ~ \#\#\#\#\#\# 로 제목 크기에 따라 h1 ~ h6을 나타낸다.

```
# h1
## h2
### h3
#### h4
##### h5
###### h6
```

# h1

## h2

### h3

#### h4

##### h5

###### h6

2.
