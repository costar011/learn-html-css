# Ep01 - 개발 환경 구성

## 개발 이란?

- 개발이라는 업무를 진행 할 환경을 말한다.
- 메모장으로도 개발을 할 수 있지만 메모장으로 하면 효율이 떨어지기 때문에 코딩을 하기에 적합한 프로그램을 설치해서 사용하는 것 이다.

- vscode 안에 좌측에 보이는 막대는 Activity Bar (액티비티 바) 라는 작업 막대 영역이다
- 왼쪽에 파일을 눌러보면 파일이나 폴더 탐색기가 있는 걸 볼 수 있고 실제 작업 할 파일을 생성할 수 있다
- Side Bar (사이드 바) 영역으로 액티비티 바에서 클릭 한 기능들을 사용 할 수 있는 영역이다
- 에디터 영역으로 실제로 우리가 html, css 파일을 만들고 해당 영역에서 코딩을 할 수 있다

<img src="https://code.visualstudio.com/assets/api/ux-guidelines/examples/activity-bar.png" alt="Activity-Bar" width="500" height="400">

</br>
</br>

# 확장 프로그램 설치

<img src="https://ms-ceintl.gallerycdn.vsassets.io/extensions/ms-ceintl/vscode-language-pack-ko/1.99.2025031909/1742376468482/Microsoft.VisualStudio.Services.Icons.Default" alt="language-pack-ko" width="100" height="100">

<img src="https://oderwat.gallerycdn.vsassets.io/extensions/oderwat/indent-rainbow/8.3.1/1649543509070/Microsoft.VisualStudio.Services.Icons.Default" alt="indent-rainbow" width="100" height="100">

<img src="https://coenraads.gallerycdn.vsassets.io/extensions/coenraads/bracket-pair-colorizer-2/0.2.4/1648139476572/Microsoft.VisualStudio.Services.Icons.Default" alt="bracket-pair-colorizer" width="100" height="100">

<img src="https://formulahendry.gallerycdn.vsassets.io/extensions/formulahendry/auto-rename-tag/0.1.10/1644319230173/Microsoft.VisualStudio.Services.Icons.Default" alt="auto-rename-tag" width="100" height="100">

<img src="https://pranaygp.gallerycdn.vsassets.io/extensions/pranaygp/vscode-css-peek/4.4.3/1741158075184/Microsoft.VisualStudio.Services.Icons.Default" alt="css-peek" width="100" height="100">

<img src="https://solnurkarim.gallerycdn.vsassets.io/extensions/solnurkarim/html-to-css-autocompletion/1.1.2/1566185298296/Microsoft.VisualStudio.Services.Icons.Default" alt="html-to-css" width="100" height="100">

<img src="https://ecmel.gallerycdn.vsassets.io/extensions/ecmel/vscode-html-css/2.0.13/1737702889132/Microsoft.VisualStudio.Services.Icons.Default" alt="html-css" width="100" height="100">

<hr/>

# Ep02 - HTML이란 무엇인가?

## HTML이란?

- HTML 은 Hyper Text Markup Language 인데 여기서 Hyper 라는 사전적 의미는 최고의, 과도한 이라는 뜻으로 일반적인 문서보다 최고의 기능을 담고 있는 문서라고 보면 된다

- 그 기능 중에 대표적인 기능이 바로 Hyper Link 라는 기능인데 이 기능은 텍스트를 클릭하면 링크된 다른 웹 문서로 이동하는 문서 연결 기능이다

## Markup 은 인쇄 원고에서 교정 표시를 나타나는 표시로서 말 그대로 마크 하는 것이다

- 웹 문서에서는 특정 텍스트의 문서를 마크하기 위하여 html의 태그라는 것을 사용한다

- 제목과 같이 크게 볼 수 있도록 텍스트를 마크 하려면 h1이라는 태그를 사용한다

- 문단을 나타낼 때는 p태그, Hyper Link를 나타낼 때는 a태그 라는 것을 사용한다

# 결론 : HTML 은 Hyper Text Markup Language 약자이며 태그를 이용한 Markup 언어이다

<hr/>

- HTML tag는 특징, 구조
- 웹 접근성 - 웹 접근성은 장애를 가진 사람과 장애를 가지지 않은 사람 모두가 웹사이트를 이용할 수 있게 하는 방식

- HTML 문서 기본구조
- 기본적으로 선언되야 하는 것 : doctype , html, head, body

- HTML 주석
- <!— —> 이렇게 표시함

# Ep03 - Emmet

## Emmet이란? HTML과 CSS 의 자동완성 기능을 제공하여 작성 시간을 아주 빠르게 단축 시켜주는 확장 기능이다

### HTML 표준 구조 `!`

`! 입력 후 Tab키` 간단하고 빠르게 HTML 기본 구조를 만들어준다

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

<hr/>

```html
<div>
  <ul>
    <li></li>
    <li></li>
    <li></li>
  </ul>
</div>

<div>
  <ul></ul>
  <ol></ol>
  <div></div>
</div>

<div>
  <ul>
    <li></li>
    <li></li>
    <li></li>
  </ul>
</div>

<span class="title"></span>
<div class="title"></div>

<p class="container">Hello world~!</p>

<p class="container">item1</p>
<p class="container">item2</p>
<p class="container">item3</p>
<p class="container">item4</p>
<p class="container">item5</p>
```

<br/>
<hr/>

## width, height

`.item{h100+w100} 입력 후 Tab키` width, height를 지정할 수 있다
기본값은 px 단위이며 단위를 교체하는 것도 가능하다

- 기본값 → px
- p → %
- e → em
- x → ex
- r → rem

<br/>
<hr/>

# Ep04_1 - HTML 폰트(Font) 태그

## 글꼴 관련 태그

`<h1> ~ <h6>` Heading

웹 페이지의 제목 또는 부제목을 표현할 때 사용하며 숫자가 적을수록 큰 제목을 표시하는 데 사용

`<p>` Paragraph

하나의 문단을 표시할 때 사용

`<hr>` Horizontal Rule

가로로 선을 긋는 태그 (종료태그 없음)

`<br>` Break

줄바꿈 태그로 HTML 개행 역할을 함 (종료태그 없음)

`<i>`Italic

텍스트를 _이텔릭체으로 표시_ 할 때 사용

`<em>` Emphasis

텍스트를 _이텔릭체으로_ 할 때 사용

`<b>` Bold

텍스트를 **진하게** **표시** 할 때 사용

`<string>`

텍스트를 **진하게 강조** 할 때 사용

`<b> vs <strong>` 차이, `<i> vs <em>`차이

`b` 태그와 `strong` 태그 모두 **진하게** 표시할 때 사용하고,

`i` 태그와 `em` 태그 모두 *이텔릭체*로 표시할 때 사용

하지만 이 두 태그의 사용 용도는 크게 다르다

- b태그와 i 태그는 단순히 텍스트를 진하게 그리고 이텔릭체로 표시하는 역할만 한다
- strong 태그와 em 태그는 실제로 페이지 내의 중요한 부분으로 강조하고 싶을 때 사용
  → strong, em 태그를 용도에 맞게 사용하면 웹 접근성에 큰 기여를 한다

브라우저에서는 스크린리더(Screen Reader)를 사용하는 경우

음성합성(Speech Synthesizer) 도구가 페이지를 해석하고 읽어낼 때

strong 태그에 대해 거센 억양으로 음을 낼 수 있도록 하여 실제로 말할 때의 강조를 하듯이 재구성 할 수 있게 됨

- 스크린리더란?
  → 시각장애인이 컴퓨터를 사용할 때 화면에 나타나는 정보들을 음성으로 출력해주는 화면낭독 프로그램

# Ep04_2 - HTML 목록(List) 태그

## 목록 태그

`<ol>` Order List

**순서가 있는 목록**을 표현할 때 사용

- type 속성으로 글머리 기호를 변경할 수 있음

`<ul>` Unordered Lists

**순서가 없는 목록**을 표현할 때 사용

`<li>` Listed Item

목록하위항목으로 사용되며 `<ul>` 태그 또는 `<ol>` 태그의 하위에 위치

`<dl>` Definition List

Definition List (정의 목록) 약자로 **사전처럼 용어를 설명하는 목록**

`<dt>` Definition Term

Definition Term (정의 용어)의 약자로 정의되는 **용어의 제목**을 넣을 때

`<dd>` Definition Description (정의 설명)

**용어를 설명**하는데 사용

### 주의사항

`<dl>` 태그는 하나 이상의 `<dt>-<dd>` 쌍의 태그를 갖고있어야 함

- 단 `<dt>-<dd>` 태그가 반드시 하나의 짝으로 지어져야 하는 것은 아님

`<li>` , `<dt>-<dd>` 태그는 밖에서 독립적으로 사용할 수 없음

`<ul>` 태그 하위요소로는 `<li>` 태그가 위치해야 함

# Ep04_3 - HTML 표(Table) 태그

## 표(Table) 태그

### Table 구조

![스크린샷 2025-03-30 오후 5.47.30.png](attachment:e465d8e3-9f37-4236-a26c-26d45f659873:스크린샷_2025-03-30_오후_5.47.30.png)

- `<table>` 태그 - 표
- `<tr>` 태그 - 행
- `<td>` 태그 - 열

## Table 기본 태그

- `<table>` 표를 만드는 태그 , 표 전체를 감싸는 데 사용
- `<caption>` 표의 제목이나 설명을 작성하는 태그
- `<tr>` 표의 행을 의미하는 태그 자식으로 `<th>` 태그나 `<td>` 태그가 반드시 있어야 함
- `<th>` 표의 **제목 열**을 의미하는 태그 부모 태그인 `<tr>` 태그 안에 있어야 함
- `<td>` 표의 **일반 열**을 의미하는 태그 부모인 `<tr>` 태그 안에 있어야 함

## Table 그룹 관련 태그

- `<colgroup>` 열을 그룹으로 묶을 수 있도록 해주는 태그
- `<col>`
  - `<colgroup>` 태그의 자식으로 열 단위를 나눌 수 있음
  - `span` 속성을 사용하여 열을 그룹으로 묶을지 선정 함
    Ex) <col span=”3”> → 세 개의 열을 그룹으로 묶음
- `<thead>` 표의 제목 열 들을 묶는 그룹 태그
- `<tbody>` 표의 일반적인 데이터들을 묶는 그룹 태그
  - 기본적으로 행 그룹 태그를 사용하지 않으면 크롬브라우저가 자동으로 tbody 태그로 묶음
- `<tfoot>` 표의 하단 영역을 묶는 그룹 태그

## Table 태그 관련 속성

- `<table>` 태그 속성
  - border - 테이블이 갖고 있는 테이블과 셀 모두 선을 표시 `웹표준 X`
  - width - 테이블의 가로너비를 설정 `웹표준 X`
  - cellpadding - **셀의 안쪽 여백**으로써 셀과 콘텐츠와의 간격을 조절함 `웹표준 X`
  - cellspacing - **셀의 밖깥쪽 여백**으로써 셀과 셀간의 간격을 조절함 `웹표준 X`
    **위 속성들은 XHTML 1.0에서는 웹 표준이지만 오늘날 HTML5 에서는 웹 표준이 아님**
    **→ CSS 로 대체해야 함**
- `<th>`
  - scope - 웹접근성 관련 속성으로 스크린리더가 데이터를 인식하고 읽는 순서를 결정짓게 함
  - th가 **열에 쓰일 경우** 값을 “col” 로 설정 함
    - 예시 ) `<th scope="col">`
  - th가 **행에 쓰일 경우** 값을 “row”로 설정 함
    - 예시) `<th scope="row">`
- `<th>` `<td>`
  - colspan - 열을 병합하는 속성
    - 예시) `<td colspan="2">`
  - rowspan - 행을 병합하는 속성
    - 예시) `<td rowspan="2">`
- `<col>`
  - width - 열의 가로 넓이를 지정하지만 `웹표준 X` → CSS로 대체
  - span - 열을 그룹화 함
    - 예시) `<col span="3">` → 3개의 열을 묶음

## Ep04_3 - HTML 표(Table) 태그

## 표(Table) 태그

### Table 구조

![스크린샷 2025-03-30 오후 5.47.30.png](attachment:e465d8e3-9f37-4236-a26c-26d45f659873:스크린샷_2025-03-30_오후_5.47.30.png)

- `<table>` 태그 - 표
- `<tr>` 태그 - 행
- `<td>` 태그 - 열

## Table 기본 태그

- `<table>` 표를 만드는 태그 , 표 전체를 감싸는 데 사용
- `<caption>` 표의 제목이나 설명을 작성하는 태그
- `<tr>` 표의 행을 의미하는 태그 자식으로 `<th>` 태그나 `<td>` 태그가 반드시 있어야 함
- `<th>` 표의 **제목 열**을 의미하는 태그 부모 태그인 `<tr>` 태그 안에 있어야 함
- `<td>` 표의 **일반 열**을 의미하는 태그 부모인 `<tr>` 태그 안에 있어야 함

## Table 그룹 관련 태그

- `<colgroup>` 열을 그룹으로 묶을 수 있도록 해주는 태그
- `<col>`
  - `<colgroup>` 태그의 자식으로 열 단위를 나눌 수 있음
  - `span` 속성을 사용하여 열을 그룹으로 묶을지 선정 함
    Ex) <col span=”3”> → 세 개의 열을 그룹으로 묶음
- `<thead>` 표의 제목 열 들을 묶는 그룹 태그
- `<tbody>` 표의 일반적인 데이터들을 묶는 그룹 태그
  - 기본적으로 행 그룹 태그를 사용하지 않으면 크롬브라우저가 자동으로 tbody 태그로 묶음
- `<tfoot>` 표의 하단 영역을 묶는 그룹 태그

## Table 태그 관련 속성

- `<table>` 태그 속성
  - border - 테이블이 갖고 있는 테이블과 셀 모두 선을 표시 `웹표준 X`
  - width - 테이블의 가로너비를 설정 `웹표준 X`
  - cellpadding - **셀의 안쪽 여백**으로써 셀과 콘텐츠와의 간격을 조절함 `웹표준 X`
  - cellspacing - **셀의 밖깥쪽 여백**으로써 셀과 셀간의 간격을 조절함 `웹표준 X`
    **위 속성들은 XHTML 1.0에서는 웹 표준이지만 오늘날 HTML5 에서는 웹 표준이 아님**
    **→ CSS 로 대체해야 함**
- `<th>`
  - scope - 웹접근성 관련 속성으로 스크린리더가 데이터를 인식하고 읽는 순서를 결정짓게 함
  - th가 **열에 쓰일 경우** 값을 “col” 로 설정 함
    - 예시 ) `<th scope="col">`
  - th가 **행에 쓰일 경우** 값을 “row”로 설정 함
    - 예시) `<th scope="row">`
- `<th>` `<td>`
  - colspan - 열을 병합하는 속성
    - 예시) `<td colspan="2">`
  - rowspan - 행을 병합하는 속성
    - 예시) `<td rowspan="2">`
- `<col>`
  - width - 열의 가로 넓이를 지정하지만 `웹표준 X` → CSS로 대체
  - span - 열을 그룹화 함
    - 예시) `<col span="3">` → 3개의 열을 묶음

## Ep05 - 시맨틱(Semantic) 태그

**Semantic 의 사전적 의미는 (의미론적) 임**

**Semantic 태그 이점**

- 검색엔진 최적화
- 웹 접근성 향상
- 가독성 향상

## HTML Sementic Elements

- `<header>` - 페이지에 대한 정보를 담는 태그로 페이지 상단에 위치
- `<nav>` - 다른 페이지나 같은 페이지 안에 다른 부분으로 이어주는 네비게이션 링크로 구성된 섹션을 표현
- `<aside>` - 페이지 전체 내용과는 어느정도 관련성이 있지만 주요 내용과는 직접적인 연관성은 없는 분리된 내용을 담고 있음
- `<main>` - 문서의 body 요소의 주 콘텐츠 (main content)를 정의할 때 사용
- `<section>` - 문서나 응용프로그램의 일반적인 섹션을 표현
- `<article>` - article은 여러가지 아이템들을 묶어 재사용 가능하게 그룹화 함
- `<footer>` - 주로 저작권 정보나 서비스 제공자 정보 등을 나타내며 사이트 하단에 위치
- `<details>` - 추가적인 정보를 나타내거나 사용자가 요청하는 정보를 나타냄
- `<summary>` - 부모요소인 details 요소의 내용에 대한 요약이나 캡션등을 나타냄
- `<figcaption>` - 부모요소인 figure요소의 내용들에 대한 캡션 혹은 제목을 나타냄
- `<figure>` - 일러스트, 다이어그램, 사진, 코드등에 주석을 다는 용도로 사용
- `<mark>` - 하나의 문서 내에서 다른 문맥과의 관련성을 나타내기 위해서 참조 목적으로 마킹되거나 하이라이트 된 텍스트를 표현
- `<time>` - 24시간에서의 시간 혹은 고레고리력에서의 정밀한 날짜를 나타냄

## MDN Semantics

**Semantics - 용어 사전 | MDN**

[https://www.notion.so/Ep05-Semantic-1c6d178f83ea803e9a2ef59d9ff46ca2?pvs=4#1c7d178f83ea80fbaa11cfa7c3c1f744](https://www.notion.so/Ep05-Semantic-1c6d178f83ea803e9a2ef59d9ff46ca2?pvs=21)

프로그래밍에서 시맨틱은 코드 조각의 의미는 나타냄

## Ep06 - Block 레벨 요소와 Inline 레벨 요소란?

### `<div>` 태그와 `<span>`태그는 웹 페이지의 영역을 구분할 때 사용하는 태그

`<div>`태그는 주로 분할을 하거나 어떤 태그를 담는 컨테이너의 역할을 한다

`<span>`태그는 `<div>`태그와 마찬가지로 영역 태그 이다

`<div>`**태그와** `<span>`**태그의 차이점**

`<div>`태그는 박스 형태로 요소들을 담는 컨테이너의 역할을 하면서 구분

`<span>`태그는 박스 모양이나 다른 태그들을 담는 컨테이너 보다는 특정 텍스트나 문장 영역을 지정

## `<div>`- 영역 태그, 컨테이너 (display: block)

## `<span>`- 영역 태그, 특정 아이템 ( display: inline )

# Block Element

---

블록 레벨 요소는 부모 요소의 전체 공간을 차지하여 “블록”을 만듦

`<h1>~<h6>` `<ol>` `<ul>` `<li>` `<p>` 태그 등이 블록 요소에 속함

- 화면 구성이나 레이아웃을 짤 때는 블록 레벨 요소를 사용
- 블록 레벨 요소는 한 칸을 모두 차지하기 때문에 세로로 나열
- width, height, margin 속성이 적용
- 블록 레벨 요소 목록
  `<address>` - 연락처 정보
  `<article>` - 단락 콘텐츠
  `<aside>` - 부가 콘텐츠
  `<blockquote>` - 긴 (”블록”) 인용구
  `<details>` - 상세 정보 위젯
  `<dialog>` - 대화상자
  `<dd>` - 설명 목록의 정의 설명
  `<dl>` - 설명 목록
  `<div>` - 문서의 분할
  `<dt>` - 설명 목록의 정의
  `<fieldset>` - 필드 집합의 라벨
  `<figcaption>` - 그림 설명
  `<figure>` - 미디어 콘텐츠 그룹과 설명 ( `<figcaption>` 을 참고)
  `<footer>` - 페이지나 구역의 푸터
  `<form>` - 입력 폼
  `<h1>` , `<h2>` , `<h3>` , `<h4>` , `<h5>` , `<h6>` - 1~6단계 제목
  `<header>` - 페이지나 구역의 헤더
  `<hgroup>` - 헤더 정보 그룹
  `<hr>` - 수평선 (구분선)
  `<li>` - 목록의 항목
  `<main>` - 문서에서 하나 뿐인 중심 콘텐츠
  `<nav>` - 탐색 링크를 포함
  `<ol>` - 정렬된 목록
  `<p>` - 문단
  `<pre>` - 미리 서식 적용한 글
  `<section>` - 웹 페이지의 구역
  `<table>` - 표
  `<ul>` - 정렬되지 않은 목록

# Inline Element

---

인라인 레벨 요소는 콘텐츠의 흐름을 끊지 않고 (줄 바꿈 X )

요소를 구성하는 **태그에 할당된 공간만 차지**

`<a>` `<em>` `<img>` `<span>` 태그 등이 인라인 요소에 속함

- 인라인 레벨 요소는 콘텐츠 영역 만큼 차이나기 때문에 가로로 나열
- margin-top, margin-bottom 적용되지 않음 대신 line-height 이용
- width, height 속성이 적용되지 않음
- 태그가 콘텐츠의 할당 된 공간만 갖고 있기 때문에 text-align과 같은 속성 사용 할 수 없음
- 인라인 요소들
  `<a>`
  `<abbr>`
  `<acronym>` (en-US)
  `<audio>`(컨트롤이 보이면)
  `<b>`
  `<bdi>` (en-US)
  `<bdo>`
  `<big>` (en-US)
  `<br>`
  `<button>`
  `<canvas>`
  `<cite>`
  `<code>`
  `<data>`
  `<datalist>`
  `<del>`
  `<dfn>`
  `<em>`
  `<embed>`
  `<i>`
  `<iframe>`
  `<img>`
  `<input>`
  `<ins>`
  `<kbd>`
  `<label>`
  `<map>`
  `<mark>`
  `<meter>`
  `<noscript>`
  `<object>`
  `<output>`
  `<picture>` (en-US)
  `<progress>`
  `<q>`
  `<ruby>`

# css Display 속성

---

CSS의 display 속성은 요소가 화면에 어떻게 표시되는지 설정하는 역할을 한다

위에서 언급했던 것처럼 CSS default pisplay value가 block이면 해당 태그는 블록 요소이고

inline이면 inline 요소이다

display 속성의 값을 변경함으로써 시각적인 표현을 변경할 수 있음

즉, 블록 요소를 인하인 요소 등으로 바꿀 수 있다

```css
/* 블록 요소인 div를 인라인 요소로 변경 */
div {
  display: inline;
}
```

# 속성값

- `none` - 보이지 않음
- `block` - block 요소로 표시
- `inline` - inline 요소로 표시
- `inline-block` - block과 inline의 중간 형태로 요소는 inline인데 내부는 block 처럼 표시
- `flex` - layout 만들 때 자주 사용하는 값으로 뒤에서 자세히 다룰 예정

## 학습정리

- div, span

div, span 둘 다 영역태그

div는 영역을 분할 하며 컨테이너의 역할도 함

span은 영역 태그 이며 특정 아이템을 꾸밀때 사용

- block VS inline

div는 block level element ( 전체공간, 세로배치, width&height 적용O )

span은 inline level element ( 콘텐츠만큼, 가로배치, width&height 적용X )

## Ep07_1,Ep07_2 이미지 & 멀티미디어 태그

# 이미지 태그

---

`<img>` 태그는 HTML 문서에 이미지를 넣는다

```html
<img src="img/apple.jpg" alt="사과" />
```

위 예제를 통해 `<img>` 요소의 사용법을 알 수 있음

## 속성

- `src`
  - **필수**이며 이미지로의 경로를 지정
- `alt`
  - 이미지의 텍스트 설명이며 필수는 아니지만 스크린 리더가`alt` 의 값을 읽어 사용자에게
    이미지를 설명하므로 웹 접근성 차원에서 **매우 유용**하다
    또한 네트워크 오류, 콘텐츠 차단, 죽은 링크 등 이미지를 표시할 수 없는 경우에도
    이 속성의 값을 대신 보여줌
- `height`
  - 픽셀 단위의 이미지의 고유 크기, 단위 없는 정수여야 함
- `width`
  - 이미지의 픽셀 기준 고유 너비, 단위 없는 정수여야 함

## 이미지 - src, alt

# 절대경로 VS 상대경로

### 절대 경로

리소스(이미지)의 절대 경로는 말 그대로 절대적인 고유한 경로를 지정하는 것

- 웹 이미지 절대경로 예시) http://www.naver.com/apple.png
  http 프로토콜로 시작해서 전체 경로를 입력
- 웹 이미지 절대경로 예시) /apple.png
  루트(’/’) 디렉터리부터 시작하는 경우 현재 도메인이 자동으로 앞에 붙음
- PC 컴퓨터 절대경로 예시) C:\user\gymcoding\apple.png

그러나 절대경로를 이용하면 웹에서 이미지가 사라지거나

내 컴퓨터에서 만든 파일을 다른 곳으로 옮길 때 해당 절대경로를 다시 수정해야 하는 불편함이 있음

그래서 작업중인 폴더에 이미지를 옮기고 상대적인 위치를 가리킴으로써 이러한 불편함을 해소할 수 있음

### 상대 경로

상대경로는 현재 문서를 기준으로 경로를 인식하는 방법

- `index.html` 에서 동일한 위치에 있는 apple.png를 가져오는 방법 → `src="apple.png"` 또는
  `src="./apple.png"`
- `index.html` 의 상위 폴더에 이미지가 있는 경우 → `src="../apple.png"`
- `index.html` 의 하위 폴더에 이미지가 있는 경우 → `src="하위폴더/apple.png"`

## 절대: http~ , /~

## 상대: ./ ../

## 오디오 태그

---

`<audio>` 태그는 HTML문서에 소리 콘텐츠를 넣을 때 사용

`src` 속성 또는 `<source>` Element를 사용하여 한 개 이상의 오디오 소스를 지정할 수 있으며

다수를 지정한 경우 가장 적절한 소스를 브라우저가 선택함

```html
<!-- src 속성을 사용 -->
<audio controls src="/media/cc0-audio/t-rex-roar.mp3">
  <!-- source 요소를 사용 -->
  <audio controls>
    <source src="myAudio.mp3" type="audio/mpeg" />
    <source src="myAudio.ogg" type="audio/ogg" />
  </audio>
</audio>
```

# 비디오 태그

---

`<video>` 태그는 영상 콘텐츠를 HTML문서에 삽입할 때 사용

`src` 속성 또는 `<source>` Element를 사용하여 한 개 이상의 오디오 소스를 지정할 수 있으며

다수를 지정한 경우 가장 적절한 소스를 브라우저가 선택함

```html
<!-- src 속성을 사용 -->
<video controls src="">
  <!-- source 요소를 사용 -->
  <video controls width="250">
    <source src="" type="audio/mpeg" />
    <source src="" type="audio/ogg" />
  </video>
</video>
```

# 오디오 & 비디오 태그 속성

---

- `controls` - 플레이어 화면에 컨트롤 바 (재생막대)를 표시
- `autoplay` - 오디오나 비디오를 자동으로 실행
  - 단, 크롬, 파이어폭스 브라우저는 자동 재생을 지원하지 않기 때문에 만약 자동 재생을 하고 싶다면
    `muted` 속성을 사용하여 소리를 제거해야 함
- `loop` - 오디오나 비디오를 반복 재생
- `muted` - 오디오나 비디오의 소리를 제거
- `preload` - 페이지를 불러올 때 오디오나 비디오 파일을 어떻게 로딩할 것인지 지정
  - 사용할 수 있는 값은 `auto` `metadata` `none` 이다
- `width` `height` - 비디오 플레이어의 너비와 높이 지정
  - `width` 나 `height` 의 값 중에서 하나만 지정하면 나머지는 자동으로 계산해서 표시
- `poster="파일 이름"` - `<video>` 태그에서 사용하는 속성으로 비디오가 재생되기 전까지 화면에 표시될 포스터 이미지를 지정

# 하이퍼링크 태그

`<a>` 태그는 `href` 속성을 사용하여 **다른 페이지**나 같은 페이지의 **특정위치**, 파일, 이메일 주소와 그 외 다른

URL 로 연결할 수 있는 하이퍼링크를 만든다

`target="_blank"` 속성을 사용하여 새탭에서 화면을 열 수 있다

- 같은 폴더안에 있는 다른 페이지로 이동

```html
<a href="inner.html"> 다른 페이지 이동 </a>
<a href="inner.html" target="_blank">새탭으로 페이지 열기</a>
```

- 이미지에 하이퍼 링크 걸기

```html
<a href="inner.html"><img src="apple.png" alt="사과" width="200" /></a>
```

- ID 속성이 apple 특정위치로 이동하는 하이퍼링크

```html
<!-- id가 apple인 요소로 이동하는 하이퍼링크 -->
<a href="#apple">이동</a>

<!-- 해당 요소 위치로 스크롤이 이동함 -->
<a href="apple">사과</a>
```

- 이메일 보내기 하이퍼링크

```html
<a href="faner4567@gmail.com">이메일 보내기</a>
```

# 속성

- `href` - 하이퍼링크가 가리키는 URL
  - 링크는 HTTP 기반 URL일 필요는 없고, 브라우저가 지원하는 모든 URL 스킬을 사용할 수 있음
    - 페이지 구획을 가리키는 프래그먼트 URL
    - 미디어 파일 일부를 가리키는 미디어 프래그먼트
  - `tel` - URL을 사용하는 전화번호
  - `mailto` - URL을 사용하는 이메일 주소
  - 웹 브라우저는 다른 URL 스킬을 지원하지 않지만
    웹사이트는 `Navigator.registerProtocolHandler()` 를 통해 지원할 수 있음
- `target`
  - `_self` - URL을 현재 브라우징 맥락에 표시함 (기본값)
  - `_blank` - URL을 새로운 브라우징 맥락에 표시함
    - 보통 새 탭 이지만 사용자가 브라우저 설정을 통해 새 창으로 바꿀 수 있음
  - `_parent` - URL을 현재 브라우징 맥락의 부모에 표시함
    - 부모가 존재하지 않으면 `_self` 와 동일하게 행동함
  - `_top` - URL을 최상단 브라우징 맥락 ( 현재 맥락의 부모면서 자신의 부모가 존재하지 않는
    제일 높은 맥락)에 표시함 부모가 존재하지 않으면 `_self` 와 동일하게 행동

## Ep08_1, Ep08_2 - Form(폼) 태그

# HTML Form 다루기 1

HTML 에서 Form은 웹에서 사용자의 정보를 입력받기 위해 사용됨

예를 들면 로그인, 회원가입, 게시판 글쓰기 등

우리는 사용자의 데이터를 입력받아 이러한 데이터를 입력 받는데,

이때 입력받는 데이터들의 묶을 폼(Form) 그리고 데이터를 폼 데이터(Form Data) 또는

필드(Field) 라고 한다

## 즉, 폼(Form)은 사용자의 정보를 입력받을 수 있게 만들어놓은 형식

# 폼 태그

`<form>` 요소는 정보를 제출하기 위하여 어디서부터 어디까지가 양식인지 지정하는 역할을 함

```html
<form action="/signup" method="post">
	<div class="form-example">
		<label for="name"> 이름: <label>
		<input type="text" name="name" id="name" required>
	</div>
	<div class="form-example">
		<label for="email"> 이메일: </label>
		<input type="email" name="email" id="email" required>
	</div>
	<div class="form-example">
		<input type="submit" value="제출하기">
	</div>
</form>
```

## 속성

- `action` - 양식 데이터를 처리 할 서버 프로그램 URL
- `method` - 양식을 제출할 때 사용할 HTTP 메소드
  - `post` - 양식 데이터를 요청 본문으로 전송
  - `get` - 양식 데이터를 URL의 쿼리스트링으로 붙여서 전송

# Input 태그

---

`<input>` 요소로 데이터를 입력 받을 수 있다

`type` 속성을 통하여 다양한 방법으로 데이터를 받을 수 있다

# Text

---

`<input>` 태그의 기본값으로 한줄의 텍스트를 입력 받음

```html
<input type="text" id="name" />
```

HTML5 에서는 text 필드가 데이터 용도에 맞게 사용 할 수 있도록 다양한 타입 추가

- `email` - email 데이터를 받기 위해 사용 ( 이메일 유효성 검증 )
- `tel` - 전화번호를 받기 위해 사용 (모바일 접근시 키패드가 다름 )
- 더 많은 `type` 은 MDN 사이트에서 참고

# label

---

`<label>` 레이블 태그는 입력받는 필드를 설명할 때 사용 `웹접근성 준수`

사용방법은 `<label>`태그 하위에 `<input>` 태그를 위치시킬 수 있고 `id` 와 `for` 속성을 사용하여

`<input>` 태그와 연결지을 수 있다

```html
<!-- label 태그 하위에 놓는 법 -->
<label>
  이름:
  <input type="text" id="name" />
</label>

<!-- for와 id속성을 사용하여 label태그와 연결 지음 -->
<label for="name"> 이름: </label>
<input type="text" id="name" />
```

# Form 데이터 태그 속성

- `required` - 입력값이 필수라는 것을 명시할 수 있음
- `readonly` - 필드를 읽기전용으로 필드로 만들 수 있음
- `disabled` - 비활성화 시킬 수 있으며 해당 필드는 서버로 전송되지 않음
- `autofocus` - 초기에 해당 필드에 커서를 위치 시킬 수 있음
- `placeholder` - 입력 필드가 비어있을 때 해당 입력값의 설명 또는 가이드 문구를 삽입할 수 있음

# fieldset

---

양식의 여러 컨트롤과 레이블 (<label>)을 묶을 때 사용

## legend

요소는 부모 `<fieldset>` 콘텐츠의 설명을 나타냄

## Checkbox

여러개의 체크박스 항복 중 2개 이상 선택할 수 있음

체크박스 선택시 선택된 체크박스의 `value` 값이 서버로 전송됨

```html
<ul>
  <li>
    <label for="apple"> 사과 </label>
    <input id="apple" type="checkbox" value="apple" />
  </li>
  <li>
    <label for="orange"> 오렌지 </label>
    <input id="orange" type="checkbox" value="orange" />
  </li>
  <li>
    <label for="banana"> 바나나 </label>
    <input id="banana" type="checkbox" value="banana" />
  </li>
</ul>
```

## radio

여러개의 라디오 항목 중 1개를 선택할 수 있음

라디오 항목 선택시 선택된 항목의 `value` 값이 서버로 전송

여러개 중 하나를 선택하게 하려면 그 여러 항복의 `<radio name="">` `name` 속성값을 같은 값으로

그룹핑 해줘야 함

```html
<ul>
  <li>
    <label for="strawberry"> 딸기 </label>
    <input id="strawberry" name="fruit" type="radio" value="strawberry" />
  </li>
  <li>
    <label for="grape"> 포도 </label>
    <input id="grape" name="fruit" type="radio" value="grape" />
  </li>
  <li>
    <label for="peach"> 복숭아 </label>
    <input id="peach" name="fruit" type="radio" value="peach" />
  </li>
</ul>
```

# HTML Form 다루기 2

`<input>` 태그 에서는 주로 한줄 데이터를 `type` 에 의해 다양한 방 입력 받음

`<form>` 양식을 전송할 때는 `<input>` 태그 말고 다양한 요소를 사용할 수 있음

Textare

Select

Datalist

Button

type

## Textarea

---

`<textarea>` 는 여러줄의 데이터를 입력받을 수 있음

```html
<textarea id="story" name="story" rows="5" cols="33">
	It was a dark and stormy night...
</textarea>
```

### 속성

- `rows` - 화면에 표시되는 행수르
- `cols` - 화면에 표시되는 컬럼 수를 지정

## Select

---

`<select>` 태그는 옵션 메뉴를 제공함 `<option>` 태그로 각 항목을 나타내며

`<select>` 태그는 `<option>` 태그를 감싸줌

```html
<select name="goods" id="goods">
  <option value="10kg">사과 10kg</option>
  <option value="20kg" selected>사과 20kg</option>
  <option value="30kg">사과 30kg</option>
  <option value="40kg">사과 40kg</option>
</select>
```

옵션 안에 있는 내용은 사용자 화면에 보여주는 내용이며 실제 서버로 전송되는 값은`value` 안의 값이다

## 속성

- `selected` 해당 속성은 현재 `<select>` 요소에서 선택된 항목 `<option>` 을 가리킨다

# Datalist

---

다른 컨트롤에서 고를 수 있는 가능한 혹은 추천하는 선택지를 나타내는 `<option>` 요소 여럿을 담는다

```html
<label for="ice-cream-choice">맛을 선택하세요</label>
<input list="ice-cream-flavors" id="ice-cream-choice" name="ice-cream-choice" />
<datalist id="ice-cream-flavors">
  <option value="Mint"></option>
  <option value="Coconut"></option>
  <option value="Vanilla"></option>
  <option value="Chocolate"></option>
</datalist>
```

# Button

---

`<button>` 요소는 클릭 가능한 버튼을 나타냄 `<form>` 내부는 물론이고 버튼기능이 필요한 곳 이라면

어디에서나 배치 할 수 있음

```html
<button type="button">추가하기</button>
```

## `Type`

버튼의 행동 방식을 선언함

- `submit` - 버튼이 서버로 양식 데이터를 제출 (기본값)
- `reset` - `<input type="reset">` 처럼 모든 입력 필드를 초기값으로 되돌림
- `button` - 기본 행동이 없으며 주로 클릭 한 후 자바스크립트 측 코드를 명령할 때 사용

## Ep09 - Head 태그

## head 태그란?

---

`<head>` 태그는 문서정보(메타데이터)를 담고 있음

브라우저 화면에 직접적으로 보이지는 않지만 숨은 데이터를 정의하는 태그들이 들어가 있음

예를들면 `<title>` `<base>` `<link>` `<style>` `<meta>` `<script>`등 이러한 태그들이 대표적인 태그

## head 안에 배치할 수 있는 요소

---

- `<title>`
  - 브라우저의 제목 표시줄이나 페이지 탭에 보이는 문서 제목을 정의
  - 텍스트만 포함할 수 있으며 태그를 포함하더라도 무시

```html
<title>naver</title>
```

- `<base>`
  - 문서 안의 모든 상대 URL이 사용할 기준 URL을 지정
  - 문서에는 하나의 `<base>` 요소만 존재할 수 있음

```html
<base href="/assets/images" />
```

- `<link>`
  - 현재 문서와 외부 리소스의 관계를 명시
  - `<link>` 는 스타일 시트를 연결 할 때 제일 많이 사용하지만
  - 사이트 아이콘 ( “파비콘” 과 홈 화면 아이콘) 연결 등 여러가지고 쓰일 수 있음

```html
<!-- 파비콘 설정 -->
<link rel="shortcut icon" href="../favicon.ico" />
```

- `<style>`
  - 스타일 규칙을 담고 있음

```html
<style>
  .title {
    color: blue;
  }
</style>
```

- `<meta>`
  - `<base>` `<link>` `<script>` `<style>` `<title>` 과 같은 다른 메타관련 요소로 나타낼 수
    없는 메타 데이터를 나타낸다

```html
<meta property="og:image" content="https://example.com/image.jpg" />
```

- `<script>`
  - 데이터나 자바스크립트 코드를 웹 문서에 포함할 때 사용

```html
<script src="javascript.js"></script>
```

# 오픈그래프 Open Graph

---

콘텐츠의 요약내용이 SNS에 게시되는데 최적화된 데이터를 가지고 갈 수 있도록 설정하는 것

## 기본적으로 웹에 설정해줘야하는 og 메타태그

```html
<meta property="og:type" content="website" />
<meta property="og:url" content="https://example.com/page.html" />
<meta property="og:title" content="Content Title" />
<meta property="og:image" content="https://example.com/image.jpg" />
<meta property="og:description" content="Description here" />
<meta property="og:site_name" content="en_US" />
<!-- 다음의 태그는 필수는 아니지만 포함하는 것을 추천함 -->
<meta property="og:image:width" content="120" />
<meta property="og:image:height" content="630" />
```

---
