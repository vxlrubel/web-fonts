# Web Fonts Collection

A curated collection of web fonts for web projects, including popular fonts like **Gilroy**, **Instrument Sans**, and more. This repository provides ready-to-use font files that can be included in your websites or applications.

## Fonts Included

- Gilroy
- Instrument Sans

## Usage

You can use these fonts locally in your projects:

### 1. Include in CSS

```css
@font-face {
    font-family: 'Gilroy';
    src: url('./fonts/Gilroy-Regular.woff2') format('woff2'),
         url('./fonts/Gilroy-Regular.woff') format('woff');
    font-weight: 400;
    font-style: normal;
}

body {
    font-family: 'Gilroy', sans-serif;
}
