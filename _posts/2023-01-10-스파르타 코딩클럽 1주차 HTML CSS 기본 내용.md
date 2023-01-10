---
layout: post
published: true
title: "스파르타 코딩클럽 1주차 HTML CSS 기본 내용"
summary: "HTML / CSS / Javascript"
author: joon
date: "2023-01-10 21:15:00 +0900"
category: Language
thumbnail: /assets/img/posts/Language/html_css_js.jpg
usemathjax: true
permalink: /blog/스파르타 코딩클럽 1주차/
---

# 스파르타 코딩클럽 1주차 HTML CSS 기본 내용

## 🎉목차

- HTML과 CSS의 개념
- 예시코드
- 연습문제 풀이 및 풀이 결과

### 1) HTML과 CSS의 개념

🦴 HTML은 뼈대, CSS는 꾸미기!

    - HTML은 구역과 텍스트를 나타내는 코드로, CSS는 잡은 구역을 꾸며주는 것으로 생각합니다. HTML 내 style 속성으로 꾸미기를 할 수 있지만, 긴 세월동안 이것을 한데 모아 볼 수 있는 CSS 파일이 탄생하게 되었습니다. HTML 코드 내에 CSS 파일을 불러와서 적용합니다.
    - 또한 CSS를 잘 사용할 줄 아는 것과, '예쁘게' 만드는 것은 다른 영역이기 때문에(붓을 잡을 줄 아는 것과 그림을 잘 그릴 줄 아는 것의 차이), 많은 경우 웹디자이너나 퍼블리셔에게 의존하게 됩니다.

- head안에는 페이지의 속성 정보를, body안에는 페이지의 내용을 담습니다.
- head 안에 들어가는 대표적인 요소들: meta, script, link, title 등
- body : 실질적인 웹페이지를 구성하기 위한 내용이 들어감

### 2) 예시코드

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>스파르타코딩클럽 | HTML 기초</title>
  </head>

  <body>
    <!-- 구역을 나누는 태그들 -->
    <div>나는 구역을 나누죠</div>
    <p>나는 문단이에요</p>
    <ul>
      <li>bullet point!1</li>
      <li>bullet point!2</li>
    </ul>

    <!-- 구역 내 콘텐츠 태그들 -->
    <h1>
      h1은 제목을 나타내는 태그입니다. 페이지마다 하나씩 꼭 써주는 게 좋아요.
      그래야 구글 검색이 잘 되거든요.
    </h1>
    <h2>h2는 소제목입니다.</h2>
    <h3>h3~h6도 각자의 역할이 있죠. 비중은 작지만..</h3>
    <hr />
    span 태그입니다: 특정 <span style="color:red">글자</span>를 꾸밀 때 써요
    <hr />
    a 태그입니다: <a href="http://naver.com/"> 하이퍼링크 </a>
    <hr />
    img 태그입니다:
    <img
      src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png"
    />
    <hr />
    input 태그입니다: <input type="text" />
    <hr />
    button 태그입니다: <button>버튼입니다</button>
    <hr />
    textarea 태그입니다: <textarea>나는 무엇일까요?</textarea>
  </body>
</html>
```

#### 실제 구현된 웹페이지

<center><img src="/assets/img/posts/Language/20230110_192303.jpg" width="100%" height="100%"></center>

### 3) 연습문제 풀이

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>로그인 페이지</title>
  </head>
  <body>
    <h1>로그인 페이지</h1>
    <p>ID: <input type="text" /></p>
    <p>PW: <input type="text" /></p>
    <button>로그인하기</button>
  </body>
</html>
```

#### 연습문제 풀이 결과

<center><img src="/assets/img/posts/Language/20230110_194124.jpg" width="30%" height="30%"></center>
