# WebFont.Hero

Package for integrating `Hero` fonts in a web environment.

![npm](https://img.shields.io/npm/v/@bu0nq/webfont.hero?style=for-the-badge)
![npm](https://img.shields.io/npm/dm/@bu0nq/webfont.hero?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@bu0nq/webfont.hero?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @bu0nq/webfont.hero
```

## Usage (CSS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```css
body {
  font-family: 'Hero', sans-serif;
}
```

### Importing

```css
@import "~@bu0nq/webfont.hero/hero.css";
@import "~@bu0nq/webfont.hero/hero-normal.css";
```

To import specific fonts, you can use:

```css
@import "~@bu0nq/webfont.hero/css/hero-200-normal.css";
@import "~@bu0nq/webfont.hero/css/hero-400-normal.css";
@import "~@bu0nq/webfont.hero/css/hero-700-normal.css";
```

## Usage (LESS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```less
body {
  font-family: 'Hero', sans-serif;
}
```

### Importing

```less
@import "~@bu0nq/webfont.hero/hero";
@import "~@bu0nq/webfont.hero/hero-normal";
```

To import specific fonts, you can use:

```less
@import "~@bu0nq/webfont.hero/less/hero-200-normal";
@import "~@bu0nq/webfont.hero/less/hero-400-normal";
@import "~@bu0nq/webfont.hero/less/hero-700-normal";
```

## Usage (SCSS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```scss
body {
  font-family: 'Hero', sans-serif;
}
```

### Importing

```scss
@use "~@bu0nq/webfont.hero/scss/hero";
@use "~@bu0nq/webfont.hero/scss/hero-normal";
```

To import specific fonts, you can use:

```scss
@use "~@bu0nq/webfont.hero/scss/hero-200-normal";
@use "~@bu0nq/webfont.hero/scss/hero-400-normal";
@use "~@bu0nq/webfont.hero/scss/hero-700-normal";
```

## Licensing

It is important to always read the license for every font that you use. Most of the fonts in the collection use the `SIL
Open Font License v1.1`. Some fonts use the `Apache 2.0` license. The Ubuntu fonts use the `Ubuntu Font License v1.0`.
