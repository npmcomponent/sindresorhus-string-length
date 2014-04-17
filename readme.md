*This repository is a mirror of the [component](http://component.io) module [sindresorhus/string-length](http://github.com/sindresorhus/string-length). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/sindresorhus-string-length`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# string-length [![Build Status](https://travis-ci.org/sindresorhus/string-length.svg?branch=master)](https://travis-ci.org/sindresorhus/string-length)

> Get the real length of a string by correctly counting astral symbols

`String#length` errornously counts [astral symbols](http://www.tlg.uci.edu/~opoudjis/unicode/unicode_astral.html) as two characters.


## Install

```sh
$ npm install --save string-length
```

```sh
$ bower install --save string-length
```

```sh
$ component install sindresorhus/string-length
```


## Usage

```js
'𐌢'.length;
//=> 2

stringLength('𐌢');
//=> 1
```


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
