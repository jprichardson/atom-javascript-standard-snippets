JavaScript Standard Style Snippets for [Atom](http://atom.io)
=============================================================

Install
-------

Go to `Atom > Preferences...` then search for **JavaScript Standard Snippets**
in the `Packages` tab.

or..

		apm install javascript-standard-snippets


Credits
-------

This package is a fork of
- https://github.com/zenorocha/atom-javascript-snippets which is a fork of
- https://github.com/zenorocha/sublime-javascript-snippets which is a fork of
- https://github.com/jprichardson/sublime-js-snippets

So thanks to [zenorocha](https://github.com/zenorocha) for helping these snippets
come full-circle.

Why not `javascript-snippets` package? Because it doesn't adhere to
[JavaScript Standard Style](https://github.com/feross/standard) and doesn't
support ES2015.


Snippets Summary
----------------

- [Console](#console)
	- [cd => console.dir](#cd-consoledir)
	- [ce => console.error](#ce-consoleerror)
	- [cl => console.log](#cl-consolelog)
- [Control Flow](#control-flow)
	- [pe => process.exit](#pe-processexit)
- [Function](#function)
	- [fn => function](#fn-function)
	- [afn => anonymous function](#afn-anoymous-function)
- [Modules](#modules)
	- [me => module.exports](#me-moduleexports)
	- [req => require](#req-require)
- [Testing](testing)
	- [ase => assert.strictEqual](#ase-assertstrictequal)
	- [ade => assert.deepEqual](#ase-assertdeepequal)
	- [desc => describe](#desc-describe)
	- [ita => it (asynchronous)](#ita-it-asynchronous)
	- [its => it (synchronous)](#its-it-synchronous)



Console
-------

### [cd] console.dir

```js
console.dir(${1:obj})
```

### [ce] console.error

```js
console.error(${1:error})
```

### [cl] console.log

```js
console.log(${1:message})
```


Control Flow
------------

### [pe] process.exit

```js
process.exit(${1:code})
```


Function
--------

### [fn] function

```js
function ${1:methodName} (${2:arguments}) {
	${0:// body...}
}
```

### [afn] anonymous function

```js
function (${1:arguments}) {
	${0:// body...}
}
```

### [me] module.exports

```js
module.exports = ${1:name}
```

### [req] require

```js
require('${1:module}')
```


## Testing

### [ase] assert.strictEqual

```js
assert.strictEqual(${1:actual}, ${2:expected})
```

### [asd] assert.deepEqual

```js
assert.deepEqual(${1:actual}, ${2:expected})
```

### [desc] describe

```js
describe('${1:description}', function () {
	${0:// body...}
})
```

### [ita] it asynchronous

```js
it('${1:description}', function (done) {
	${0:// body...}
})
```

### [its] it synchronous

```js
it('${1:description}', function () {
	${0:// body...}
})
```



Development / Contributions
---------------------------

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

Wanna suggest new snippets? Excellent! First, make sure that they adhere to
[JavaScript Standard Style](https://github.com/feross/standard). This means
that if you suggest that any of these snippets should have semicolons, your
suggestion will be rejected :p

I have no intention of maintaining compability with my older [sublime JavaScript snippet
package](https://github.com/jprichardson/sublime-js-snippets).

This package will adhere to [semver](http://semver-ftw.org/). This means until
it's 1.0, you can and should expect breaking changes.

I'm particularly interested in ES6 (ES2015)/ES7 snippet suggestions.

Please don't suggest maintaining snippets for the sake of ES5 compatibility, it's
not gonna happen.


Alternatives
------------
- https://github.com/atom/language-javascript
- https://github.com/extrabacon/atom-turbo-javascript
- https://github.com/zenorocha/atom-javascript-snippets#afn-anonymous-function


License
-------

MIT

Copyright (c) [JP Richardson](https://github.com/jprichardson)
