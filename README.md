Custombox [![npm version](https://badge.fury.io/js/custombox.svg)](https://badge.fury.io/js/custombox) [![Travis](https://travis-ci.org/dixso/custombox.svg?branch=master)](https://travis-ci.org/dixso/custombox) [![Coverage Status](https://coveralls.io/repos/github/dixso/custombox/badge.svg?branch=master)](https://coveralls.io/github/dixso/custombox?branch=master) ![npm License](http://img.shields.io/npm/l/custombox.svg?style=flat-square "npm License")
==========

Modal dialog effects with transitions CSS3.

Usage
-----

You can install custombox through bower:

```bash
bower install custombox
```

Or through npm:

```bash
npm install custombox
```

Alternatively, download the package and reference the JavaScript and CSS files manually:

```html
<script src="dist/custombox.min.js"></script>
<link rel="stylesheet" type="text/css" href="dist/custombox.min.css">
```

## Basic usage
```js
new Custombox.modal({
  content: {
    effect: 'fadein',
    target: '#modal'
  }
}).open();
```