D2Coding Web Fonts
====
[![D2Coding license](https://img.shields.io/badge/License-OFL-blue.svg)](https://raw.githubusercontent.com/Joungkyun/font-d2coding/master/license)

D2Coding Web Font who careted by [NAVER Corp](http://dev.naver.com/projects/d2coding).

## License

Copyright &copy; NAVER Copr. All Rights Reserved.

OFL(Open Font License)

THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
OF COPYRIGHT, PATENT, TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL THE
COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL
DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM
OTHER DEALINGS IN THE FONT SOFTWARE.

## Font information

### Weights
 * Bold (700)
 * Normal (400)

### Support type
 * eot
 * woff
 * woff2
 * ttf

## Installation

Insert d2coding.css or create @font-face css to HTML:

```html
<link href="/path/d2coding.css" rel="stylesheet" type="text/css">
```

or

```css
@font-face {
  font-family: 'D2 coding';
  font-style: normal;
  font-weight: 700;
  src: url('/path/d2codingbold.eot');
  src: local('※'), local('D2Coding Bold'),
       url('/path/d2codingbold.eot?#iefix') format('embedded-opentype'),
       url('/path/d2codingbold.woff2') format('x-woff2'),
       url('/path/d2codingbold.woff') format('woff'),
       url('/path/d2codingbold.ttf') format('truetype'),
       url('/path/d2codingbold.svg') format('svg');
}
@font-face {
  font-family: 'D2 coding';
  font-style: normal;
  font-weight: 400;
  src: url('/path/d2coding.eot');
  src: local('※'), local('D2Coding'),
       url('/path/d2coding.eot?#iefix') format('embedded-opentype'),
       url('/path/d2coding.woff2') format('x-woff2'),
       url('/path/d2coding.woff') format('woff'),
       url('/path/d2coding.ttf') format('truetype'),
       url('/path/d2coding.svg') format('svg');
}

```

Adding to CSS:

```css
body {
	font-family: D2Coding, 'D2 coding', monosapce;
}
```

first, search local D2Coding font and next call D2 conding web font, and last load monospace
