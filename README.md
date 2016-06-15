# noise

> P5.js noise method

## Install

```sh
$ npm install @giuliandrimba/noise
```

## Usage

``` javascript
var noise = require("noise");

var xoff = 0.0;
function draw() {
  background(204);
  xoff = xoff + .01;
  var n = noise(xoff) * width;
  line(n, 0, n, height);
}

```
> Extracted from [P5.js documentation](https://p5js.org/reference/#/p5/noise)