# three.js

#### JavaScript 3D Component  ####

The aim of the project is to create a lightweight 3D library with a very low level of complexity — in other words, for dummies. The library provides &lt;canvas&gt;, &lt;svg&gt; and WebGL renderers.

This is a slight adaption of the original three.js code to work as a
[component](https://github.com/component/component/wiki/Components).
## Installation

    $ component install timoxley/three.js

## Usage

```js

var THREE = require('three.js')

```

## API

See [documentation](http://mrdoob.github.com/three.js/docs/52/) and
mrdoob's  
[github repo](https://github.com/mrdoob/three.js/)

## Examples

For now, I've only modified
[examples/webgl_terrain_dynamic.html](https://github.com/timoxley/three.js/blob/master/examples/webgl_terrain_dynamic.html) to work with the
component modfications.

## Build Caveats

Original three.js build system in
[utils](https://github.com/timoxley/three.js/blob/master/utils/) will
build the `three.js` lib in the `build`
folder. This file needs to be renamed as `index.js` in the project root.

## License

[MIT](https://github.com/timoxley/three.js/blob/master/LICENSE))
