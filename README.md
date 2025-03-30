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
