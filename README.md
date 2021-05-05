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

# isUndefined

> Test if a value is undefined.

<section class="installation">

## Installation

``` bash
$ npm install @stdlib/assert-is-undefined
```

</section>

<section class="usage">

## Usage

```javascript
var isUndefined = require( '@stdlib/assert-is-undefined' );
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

```javascript
var isUndefined = require( '@stdlib/assert-is-undefined' );

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
```

</section>

<!-- /.examples -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/assert-is-undefined/main/LICENSE

</section>

<!-- /.links -->
