# 설치 프로그램
- brackets (css 라이브가 편한듯)

# 유데미 기본 CSS 프로젝트 클론
[강좌](https://www.udemy.com/design-and-develop-a-killer-website-with-html5-and-css3)

# 기본설정
`box-sizing: border-box`
`font-rendering` - [링크](https://css-tricks.com/almanac/properties/t/text-rendering/)

> html

- font지정
```html
<!DOCTYPE html>
<html language="en">
    <head>
        <link rel="stylesheet" type="text/css" href="./vendors/css/grid.css">
        <link rel="stylesheet" type="text/css" href="./resources/css/style.css">
        <link href="http://fonts.googleapis.com/css?family=Lato:100,300,400,300italic" rel='stylesheet' type="text/css">
        <title>Omifood</title>
    </head>
    <body>
        <h1>Omifood</h1>
    </body>
</html>
```

> css

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    background-color: #fff;
    color: #555;
    font-family: 'Lato', 'Arial', sans-serif;
    font-size: 20px;
    font-weight: 300;
    text-rendering: optimizeLegibility;
}
```

## background
- `background-url` 로 지정
- `background-position`을 통해 축소시 어느부분을 우선해서 기준으로 축소할껀지 정한다. 

## position

## background 반투명 작업

```
background-image: linear-gradient(rgba(0, 0, 0, 0.7), #000),url(img/hero.jpg);
```



### absoulte
부모중 포지션이 설정되어 있는 기준으로 설정된다. 

- 코드잇 강좌 참조

## display

### inline-block

### block

### inline

## transition
```
transition: background-color 0.2s, border 0.2s, color 0.2s;
```

## after를 통해 넣는 방법

```
h2:after {
    display: block;
    height: 2px;
    background-color: #e67e22;
    content: " ";
    width: 100px;    
}
```
## 공부내용

### 기능 섹션에서 배우는 내용

- `:after` 클래스를 이용해서 직접 css에 내용을 입력하는 방법에 대해서 공부
- `fluid grid`를 사용하는 방법
- icons를 이용하는 방법

### food section 공부내용
- 아름다운 이미지 그리드 시스템 레이아웃 개발
- CSS를 이용해서 zoom-in 애니메이션 구현
- <img> 를 이용해서 어둡게 만드는 방법

### How it Works 공부내용
- CSS와 함께 Circle를 그리는 방법
- Sections 들을 분리하는 방법
- App Store버튼과 구글 스토어 버튼을 연결하는 방법

### City 공부내용
- 새로운 스킬셋
- 아이콘과 텍스트를 정렬
- 일반 링크등을 스타일 하는 방법

### 리뷰 섹션 공부내용
- 배경 이미지 효과를 만들자
    - `fixed`를 통해 스크롤되는 이미지 효과를 줄 수 있다.

### Pricing 섹션 공부내용
- Border radius
- Box Shadows with CSS

### 입력 폼 섹션 공부내용
- form, label, input, select등 태그 활용
- 스타일 적용

### footer 작성
- 효과적인 footer 작성방법
- social icon을 사용하는 방법

### 반응형 웹 디자인
![responsive image](20190404_171357.png)

## 반응형 웹을 위한 조언

1. Fluid grid
2. Flexiable Images
3. Media queries


### input에서 focus border 없애기
```
*:focus {
    outline: none;
}
```

## CSS 브라우저 prefixes
- Android : -webkit-
- Chrome: -webkit-
- Firefox: -moz-
- IE : -ms-
- IOS: -webkit-
- Opera: -o-
- safari: -webkit-

## 궁금점
1. 47번에서 섹션 나누기는 이해가 아직 안됨
2. 

## Brackets Plugin
1. Beautify
2. Autosave
3. Emmet
4. autoprefixer

## 참고 사이트
1. normalize
2. responsegrid
3. flatcolor
4. 0to255 (반투명정도조절)
5. https://ionicons.com/
6. CSS-TRICKS > Glyphs (특수문자표)
7. https://www.designpieces.com/2012/12/social-media-colours-hex-and-rgb/ (소셜 아이콘 색상표)
8. jsdelivr.com (javascript cdn)
9. caniuse.com (브라우저별 css3 지원 여부)
10. http://imakewebthings.com/waypoints/(특정 위치에 갔을때 이벤트 감지)
11. https://daneden.github.io/animate.css/