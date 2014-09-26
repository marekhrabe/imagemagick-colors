# ImageMagick colors

A lookup table of colors that ImageMagick knows. Mind that colors in this table are **lowercased**, so you shold lookup `LavenderBlush3` as `lavenderblush3` to get its rgb or rgba string value.

## Usage

```bash
npm install imagemagick-colors
```

```js
var colors = require('imagemagick-colors')

var name = 'LavenderBlush3'
var color = colors[name.toLowerCase()]

console.log(color) // outputs rgb(205, 193, 197)
```
