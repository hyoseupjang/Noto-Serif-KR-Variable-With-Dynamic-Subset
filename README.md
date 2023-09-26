# Noto-Serif-KR-Variable-With-Dynamic-Subset
Noto Serif KR Variable With Dynamic Subset

The Noto Serif CJK Variable fonts have not yet been announced, but are available on GitHub. (https://github.com/google/fonts/blob/main/ofl/notoserifkr/NotoSerifKR%5Bwght%5D.ttf)

I subsetted based on a CSS from the https://github.com/orioncactus/pretendard with https://github.com/black7375/font-range project to for use in a web environment. 

It is distributed under a SIL license, just like the original font license. 

### Usage 
Clone this repo, and locate CSS file on document root. And... 

```html
<link rel="stylesheet" as="style" crossorigin href="/NotoSerif.css" />
```

```CSS
@import url('/NotoSerif.css')
```