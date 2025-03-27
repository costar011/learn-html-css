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

<hr />

<div>
  <ul></ul>
  <ol></ol>
  <div></div>
</div>

<hr />

<div>
  <ul>
    <li></li>
    <li></li>
    <li></li>
  </ul>
</div>

<hr />

<span class="title"></span>
<div class="title"></div>

<hr />

<p class="container">Hello world~!</p>

<hr />

<p class="container">item1</p>
<p class="container">item2</p>
<p class="container">item3</p>
<p class="container">item4</p>
<p class="container">item5</p>

<hr />
```
