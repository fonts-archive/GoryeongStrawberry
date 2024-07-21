# 고령딸기체

[배포처 바로가기](https://www.goryeong.go.kr/kor/contents.do?IDX=409)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Goryeong Strawberry`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/GoryeongStrawberry/GoryeongStrawberry.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/GoryeongStrawberry/GoryeongStrawberry.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Goryeong Strawberry';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/GoryeongStrawberry/GoryeongStrawberry.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GoryeongStrawberry/GoryeongStrawberry.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GoryeongStrawberry/GoryeongStrawberry.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GoryeongStrawberry/GoryeongStrawberry.ttf') format('truetype');
}
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Goryeong Strawberry", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
※ 고령딸기체는 영상, 인쇄 등 다양한 매체에 누구나 무료로 자유롭게 사용가능합니다. 단, 글꼴 자체를 유료로 판매하거나 왜곡 변형할 수 없습니다.
```
