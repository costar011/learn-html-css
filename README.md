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
