# webpack-cesium

A single-file [Cesium](https://cesiumjs.org) build to use in static hosting or any build system using CommonJS formats.  Included are a gzipped and brotli compressed version, both tested using Express 4.x and the big 3 evergreen browsers (Edge,Chrome,Firefox).

## Usage

`npm install webpack-cesium`

Then require/import it to get the root Cesium object within the current scope:

```javascript
var Cesium = require('webpack-cesium');
console.log(Cesium.VERSION); //=> 1.31
```

