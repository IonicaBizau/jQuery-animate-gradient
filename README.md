# jquery-animate-gradient [![Support this project][donate-now]][paypal-donations]

Animate gradient colors.

## Installation

```sh
$ npm i --save jquery-animate-gradient
```

## Documentation

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

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:

## License

[MIT][license] © [Ionică Bizău][website]

[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2014#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md