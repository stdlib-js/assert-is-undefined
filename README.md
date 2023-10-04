<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# isUndefined

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Test if a value is undefined.



<section class="usage">

## Usage

To use in Observable,

```javascript
isUndefined = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-is-undefined@umd/browser.js' )
```
The previous example will load the latest bundled code from the umd branch. Alternatively, you may load a specific version by loading the file from one of the [tagged bundles](https://github.com/stdlib-js/assert-is-undefined/tags). For example,

```javascript
isUndefined = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-is-undefined@v0.1.1-umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var isUndefined = require( 'path/to/vendor/umd/assert-is-undefined/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/assert-is-undefined@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.isUndefined;
})();
</script>
```

#### isUndefined( value )

Tests if a `value` is `undefined`.

<!-- eslint-disable no-undefined -->

```javascript
var bool = isUndefined( undefined );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint-disable no-undefined, no-restricted-syntax, no-empty-function -->

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/assert-is-undefined@umd/browser.js"></script>
<script type="text/javascript">
(function () {

var bool;
var x;

bool = isUndefined( x );
// returns true

bool = isUndefined( undefined );
// returns true

bool = isUndefined( void 0 );
// returns true

bool = isUndefined( 'beep' );
// returns false

bool = isUndefined( 5 );
// returns false

bool = isUndefined( null );
// returns false

bool = isUndefined( true );
// returns false

bool = isUndefined( {} );
// returns false

bool = isUndefined( [] );
// returns false

bool = isUndefined( function foo() {} );
// returns false

})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/assert-is-null`][@stdlib/assert/is-null]</span><span class="delimiter">: </span><span class="description">test if a value is null.</span>
-   <span class="package-name">[`@stdlib/assert-is-undefined-or-null`][@stdlib/assert/is-undefined-or-null]</span><span class="delimiter">: </span><span class="description">test if a value is undefined or null.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/assert-is-undefined.svg
[npm-url]: https://npmjs.org/package/@stdlib/assert-is-undefined

[test-image]: https://github.com/stdlib-js/assert-is-undefined/actions/workflows/test.yml/badge.svg?branch=v0.1.1
[test-url]: https://github.com/stdlib-js/assert-is-undefined/actions/workflows/test.yml?query=branch:v0.1.1

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/assert-is-undefined/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/assert-is-undefined?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/assert-is-undefined.svg
[dependencies-url]: https://david-dm.org/stdlib-js/assert-is-undefined/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/assert-is-undefined/tree/deno
[umd-url]: https://github.com/stdlib-js/assert-is-undefined/tree/umd
[esm-url]: https://github.com/stdlib-js/assert-is-undefined/tree/esm
[branches-url]: https://github.com/stdlib-js/assert-is-undefined/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/assert-is-undefined/main/LICENSE

<!-- <related-links> -->

[@stdlib/assert/is-null]: https://github.com/stdlib-js/assert-is-null/tree/umd

[@stdlib/assert/is-undefined-or-null]: https://github.com/stdlib-js/assert-is-undefined-or-null/tree/umd

<!-- </related-links> -->

</section>

<!-- /.links -->
