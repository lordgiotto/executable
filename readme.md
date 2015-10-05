# executable [![Build Status](https://travis-ci.org/kevva/executable.svg?branch=master)](https://travis-ci.org/kevva/executable)

> Check if a file is executable using Node.js


## Install

```
$ npm install --save executable
```


## Usage

```js
const executable = require('executable');

executable('bash').then(exec => {
	console.log(exec);
	//=> true
});
```


## CLI

```
$ npm install --global executable
```

```
$ executable --help

  Usage
    $ executable <file>

  Example
    $ executable optipng
```


## License

MIT © [Kevin Mårtensson](https://github.com/kevva)
