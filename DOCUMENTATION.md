## Documentation

You can see below the API reference of this module.

### `animateGradient(jQueryElement, top, bottom, {}, {}, callback)`
Animates a gradient.

**Usage:**

```js
$.animateGradient(".jQuerySelector", [0, 0, 0], [0, 0, 0], 2000, 100, function () {});
$.animateGradient(".jQuerySelector", [0, 0, 0], [0, 0, 0], 2000, function () {});
$.animateGradient(".jQuerySelector", [0, 0, 0], [0, 0, 0], function () {});
```

#### Params
- **jQuery|String** `jQueryElement`: The jQuery element or selector.
- **Array** `top`: An array of values interpreted by `rgb()` and representing the top color.
- **Array** `bottom`: An array of values interpreted by `rgb()` and representing the bottom color.
- **** `{}`: duration The duration of animation in miliseconds (default: `1000`).
- **** `{}`: delay Delay of interval (default: `100`).
- **Function** `callback`: The callback function.

