# -HTML-

2020년도 1학년 1학기 인터넷 활용 실습 수업을 들으며 작성한 html 작업물입니다.

## 📚 과목 소개 (Course Overview)

| 항목 | 내용 |
|:----:|:-----|
| 🎓 과목명 | 인터넷 활용 실습 |
| 🏫 담당 교수 | 곽문기 교수님 |
| 🗓️ 수강 학기 | 2020-1학기 |
| 💡 주요 학습 내용 | HTML, CSS, JavaScript |
| 🧰 도구 | Visual Studio Code |
| 🧩 과제 / 프로젝트 | 네이버 로그인화면 구현, 서일대학교 홈페이지 메인화면 구현 |

# 🌐 인터넷활용실습 (Web Practice)

## 📚 교재
IT CookBook, HTML5 웹 프로그래밍 입문 (3판), 한빛미디어

---

## 📅 주차별 학습 내용

| 주차 | 주요 학습 내용 |
|------|----------------|
| 1주차 | 웹의 개념, HTML/CSS/JS 개요, 웹표준 이해 |
| 2주차 | 클라이언트-서버 구조, HTML 기본 구조 학습 |
| 3주차 | 블록요소와 인라인요소, CSS 박스모델 |
| 4주차 | 선택자(selector), position, float 개념 |
| 5주차 | 이미지 스프라이트, 웹폰트, 색상표현 |
| 6주차 | z-index, 레이아웃(Layout), UI/UX 개념 |
| 7주차 | 반응형 웹(media query), Front-End vs Back-End |
| 8주차 | JavaScript 기본 문법, 변수/함수/객체 개념 |
| 9주차 | DOM(Document Object Model) 조작 |
| 10주차 | 이벤트(event), innerHTML/innerText 구분 |
| 11주차 | 알고리즘(순차/선택/반복), 배열(Array) |
| 12주차 | 경로(path), URL 구조, escape 문자 |
| 13주차 | 반복문 제어(break, continue), 이미지 스프라이트 실습 |
| 14주차 | 웹퍼블리싱 실습 (HTML/CSS 구성) |
| 15주차 | 기말 프로젝트 및 제출 (웹디자인 or JS 이벤트 구현) |

---

## 🧱 HTML

> **역할:** 웹페이지의 구조(Structure)를 정의

### 주요 개념
- 기본 구조: `<html>`, `<head>`, `<body>`
  
- 제목 태그 `<h1>`~`<h6>`, 문단 `<p>`, 링크 `<a>`, 이미지 `<img>`
  
- 리스트: `<ul>`, `<ol>`, `<li>`
  
- 구분요소: `<div>`(block), `<span>`(inline)
  
- 속성(Attribute)과 값(Value)
  
- 메타데이터, 부모/자식/형제 관계
  
- 절대경로(`https://example.com/path`) vs 상대경로(`../path/file.html`)
  
- 시맨틱(semantic) 마크업의 중요성

### 예시
```html
<html>
  <head>
    <title>My First Page</title>
  </head>
  <body>
    <h1>Hello, HTML!</h1>
    <p>이것은 HTML의 기본 구조입니다.</p>
  </body>
</html>
```


## 🎨 CSS
> **역할:** 표현(Presentation)을 담당, HTML 구조에 디자인 적용

주요 개념
- 선택자(Selector): id, class, 속성, 가상클래스(:hover, :focus)
  
- 박스모델(Box Model): padding, border, margin, box-sizing
  
- 블록요소 vs 인라인요소
  
- 위치 지정: position(static, relative, absolute)
  
- 정렬: float, z-index, display
  
- 색상표현: #RRGGBB, rgb(), rgba()

- 폰트 및 웹폰트(Web Font)
  
- 반응형 웹(Responsive Web) — @media 쿼리
  
- 레이아웃 설계(UI/UX)

### 예시
```css
코드 복사
.container {
  width: 80%;
  margin: 0 auto;
}

#box {
  background-color: #336699;
  color: white;
  padding: 20px;
  text-align: center;
}
```

## ⚙️ JavaScript
> **역할:** 동작(Behavior)을 제어, 사용자 상호작용 구현

주요 개념
- 변수(var, let, const)

- 데이터 타입, 연산자

- 배열(Array), 객체(Object)

- 함수(Function)과 메서드(Method)

- DOM(Document Object Model) 조작
→ getElementById, querySelector, innerHTML, innerText

- 이벤트(Event): click, mouseover, keyup
→ 트리거(Trigger) + 핸들러(Handler)

- 제어문: if, for, while, break, continue

- 타이밍 함수: setTimeout(), setInterval()

- 알고리즘 기본 구조: 순차(Sequence), 선택(Selection), 반복(Iteration)

### 예시
```javascript
코드 복사
const btn = document.getElementById("btn");

btn.addEventListener("click", function() {
  alert("버튼이 클릭되었습니다!");
});
```
## 🧾 참고 사이트

## 🧾 참고 사이트

- [W3Schools](https://www.w3schools.com)
- [HTML Reference](https://htmlreference.io)
- [CSS Reference](https://cssreference.io)
- [Emmet Cheat Sheet](https://docs.emmet.io/cheat-sheet/)
- [Bootstrap](https://getbootstrap.com)
