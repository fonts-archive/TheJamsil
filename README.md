# 더잠실체

[배포처 바로가기](https://company.lottemart.com/company/font_jamsil.asp)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `The Jamsil`입니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsil.css"
  type="text/css"
/>
```

### CSS `@Import`

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsil.css");
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'The Jamsil';
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilThin.woff2') format('woff2'), 
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilThin.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilThin.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilThin.ttf') format('truetype');
}
@font-face {
  font-family: 'The Jamsil';
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilLight.woff2') format('woff2'), 
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilLight.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilLight.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilLight.ttf') format('truetype');
}
@font-face {
  font-family: 'The Jamsil';
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilRegular.woff2') format('woff2'), 
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilRegular.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilRegular.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilRegular.ttf') format('truetype');
}
@font-face {
  font-family: 'The Jamsil';
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilMedium.woff2') format('woff2'), 
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilMedium.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilMedium.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilMedium.ttf') format('truetype');
}
@font-face {
  font-family: 'The Jamsil';
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilBold.woff2') format('woff2'), 
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilBold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilBold.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilBold.ttf') format('truetype');
}
@font-face {
  font-family: 'The Jamsil';
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilExtraBold.woff2') format('woff2'), 
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilExtraBold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilExtraBold.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/TheJamsilExtraBold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link 
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/subsets/TheJamsil-dynamic-subset.css"
  type="text/css"
/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/TheJamsil/subsets/TheJamsil-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "The Jamsil", -apple-system, BlinkMacSystemFont, "Segoe UI",
  Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
더잠실체 
서체소개 
젊고, 새롭게 변화된 롯데마트 ‘더잠실체’ 
롯데마트는 기존의 노후화된 브랜드 이미지를 탈피하고자 22년 ‘Everyday New Store’로 새로운 비전을 선포하고, 고객들이 젊고 변화된 롯데마트를 경험할 수 있도록 서체개발을 진행했습니다. ‘더잠실체’는 롯데마트 브랜드 이미지와 잠실지역의 역사성을 함께 녹여낸 새로운 시도이며, 롯데의 헤리티지가 곧 잠실이라는 점에 주목하여 지역명 ‘잠실’을 서체의 이름으로 선정하였습니다. ‘더잠실체’는 국문, 영문 외 베트남 및 인도네시아어까지 개발하여 해외에서도 한글의 아름다움을 느끼고, 대한민국을 대표하는 지역으로서의 ‘잠실’을 알리는 것을 최종 목표로 하고있습니다. 
 
서체컨셉 
‘잠실’은 ‘누에를 치는 방’을 의미합니다 
잠실은 ‘누에를 치는 방’이라는 뜻으로, 과거 잠실지역은 양잠을 장려하던 곳이었습니다. 
서체 디자인에 앞서 롯데의 해리티지 ‘잠실’을 어떻게 새롭게 보여줄 수 있을지 고민했고, 잠실의 옛 상징 ‘누에’를 담아보고자 했습니다. 
 
형태적 특징 
1. 누에의 일생을 담았습니다 
더잠실체는 누에가 뽕잎을 먹기위해 머리를 드는 모습부터, 누에고치를 만드는 과정, 그리고 마지막으로 누에고치에서 실을 뽑아내는 모습을 현대적으로 해석하고 적용하여 새롭게 변화된 롯데마트다움을 잘 표현한 서체입니다. 
 
누에고치 
한글 서체의 인상을 결정짓는 가장 중요한 ‘O’꼴에 누에고치의 둥글고 길쭉한 모양을 적용하여, 잠실의 헤리티지와 롯데쇼핑의 단단한 내실을 표현 
 
명주실 
흐트러짐 없이 뽑아져 나오는 명주실의 모습에서 생동감을 느끼고, 최상의 결과물을 뽑아 내는 롯데마트의 엄격한 기준을 상징 
 
누에머리 
‘모음’의 특징은 잠두마제(서예의 근간이 되는 필법)에서 아이디어를 얻어, 획의 끝 부분에 누에머리 형상을 현대적으로 표현 
2. 작은글씨부터 큰 글씨까지 모두 읽고 보는데 불편함이 없습니다 
 
3. 여섯가지 굵기로 어디에나 사용하기 편리합니다 
 
더 많은 활용예시 
 
Download 
더잠실체는 기업이나 개인 모두 무료로 사용 가능합니다. 
아래 버튼을 눌러 더잠실체를 다운로드 받으세요. 
더잠실체 OTF 더잠실체 TTF 
[더잠실 글꼴 사용 조건 및 안내] 
더잠실체의 지적재산권은 모두 롯데쇼핑(주)롯데마트사업부(이하, "롯데마트")에 있습니다. 더잠실체는 무료로 사용할 수 있으며, 본 사용규정 안내 전문을 포함하여 재배포하실 수 있습니다. 
정확한 사용 조건은 아래 라이선스 전문을 참고하시기 바랍니다. 
* 상세 사용규정 * 
1. 사용 제한 및 조건 
1) 더잠실 글자체는 인쇄나 출판, 영상, 웹, 모바일 등에 자유롭게 사용할 수 있습니다. 
2) 더잠실 글자체를 수정하거나 다른 포맷으로 변형하여 사용하는 것은 엄격하게 금지됩니다. 
3) 더잠실 글자체는 폰트 소프트웨어 또는 개별 구성요소인 폰트 자체로 유료로 판매할 수 없습니다. 
4) 더잠실 글자체는 전체나 부분 여부에 상관 없이 저작권자 안내와 본 라이선스 규정 내용을 포함하는 경우에는 다른 소프트웨어와 함께 묶이거나 재배포가 가능합니다. 
5) 더잠실 글자체가 사용된 인쇄물, 광고물(온라인 포함) 이미지 등은 롯데마트가 홍보 목적을 위해 활용할 수 있습니다. 이를 원치 않는 사용자는 언제든지 당사 고객센터로 요청 부탁드립니다. 
6) 본 라이선스는 상기 조건 중 일부라도 부합되지 않으면 무효가 될 수 있습니다. 
7) 롯데마트는 더잠실 글자체의 사용 또는 기타 더잠실 글자체의 취급과 관련하여 발생하는 어떠한 책임도 가지지 않습니다.
```
