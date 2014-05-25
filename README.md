jQuery-animate-gradient
=======================

A small jQuery library designed for one thing: animate gradients

## How to use
Animates a background gradient providing the following parameters:

 - `jQueryElement`: jQuery selector / jQuery object
 - `top`: an array of values for rgb();
 - `bottom`: an array of values for rgb();
 - `duration` (default: 1000ms): the duration of animation in miliseconds (default: 1000)
 - `delay` (default: 100ms): delay of interval (default: 100);
 - `callback`: the function that will be called after animation is done

## Examples

```js
// provide duration and delay
$.animateGradient(".jQuerySelector", [r, g, b], [r, g, b], 2000, 100, function () {});
// provide duration only
$.animateGradient(".jQuerySelector", [r, g, b], [r, g, b], 2000, function () {});
// don't provide duration
$.animateGradient(".jQuerySelector", [r, g, b], [r, g, b], function () {});
```

## Changelog

### `v0.1.0`
 - Initial release

## License
See the [LICENSE](./LICENSE) file.
