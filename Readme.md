*This repository is a mirror of the [component](http://component.io) module [yields/wrap](http://github.com/yields/wrap). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-wrap`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# wrap

  Wrap an element.

## Installation

    $ component install yields/wrap

## Example

```js
var domify = require('domify');
var p = document.querySelector('p');
var div = domify('<div></div>')[0];
wrap(p, div);
```

## API

### wrap(el, wrap)

Wraps `el` with `wrap`.

## License

  MIT
