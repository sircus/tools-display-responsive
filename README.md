# sircus-tools-display-responsive

[![npm version](https://img.shields.io/npm/v/sircus-tools-display-responsive.svg?style=flat)](https://www.npmjs.com/package/sircus-tools-display-responsive)

## Dependencies
- [sircus-global-property](https://github.com/sircus/global-property)


## Installation

> npm:

```bash
$ npm install sircus-tools-display-responsive sircus-global-property
```

## Usage

> cssnext:

input.css
```css
@import "sircus-tools-display-responsive";
/*
@import "sircus-tools-display-responsive/lib/base";
@import "sircus-tools-display-responsive/lib/sm";
@import "sircus-tools-display-responsive/lib/md";
@import "sircus-tools-display-responsive/lib/lg";
*/
@import "sircus-global-property";
```

> sass:

input.scss
```scss
@import "./node_modules/sircus-global-property/converted";
@import "./node_modules/sircus-tools-display-responsive/converted";
// @import "./node_modules/sircus-tools-display-responsive/scss/base";
// @import "./node_modules/sircus-tools-display-responsive/scss/sm";
// @import "./node_modules/sircus-tools-display-responsive/scss/md";
// @import "./node_modules/sircus-tools-display-responsive/scss/lg";
```


> html

```html
<div class="t-sm-none"></div>
<div class="t-sm-block"></div>
<div class="t-sm-inlineBlock"></div>
<div class="t-sm-inline"></div>

<div class="t-md-none"></div>
<div class="t-md-block"></div>
<div class="t-md-inlineBlock"></div>
<div class="t-md-inline"></div>

<div class="t-lg-none"></div>
<div class="t-lg-block"></div>
<div class="t-lg-inlineBlock"></div>
<div class="t-lg-inline"></div>
```


## Contributing

We Need Your Help!


## License
Released under the [MIT](https://github.com/sircus/license/blob/master/LICENSE) license.
