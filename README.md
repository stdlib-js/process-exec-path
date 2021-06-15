<!--

@license Apache-2.0

Copyright (c) 2020 The Stdlib Authors.

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

# Executable Path

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] [![dependencies][dependencies-image]][dependencies-url]

> Absolute pathname of the executable which started the current Node.js process.

<section class="installation">

## Installation

```bash
npm install @stdlib/process-exec-path
```

</section>

<section class="usage">

## Usage

```javascript
var EXEC_PATH = require( '@stdlib/process-exec-path' );
```

#### EXEC_PATH

Absolute pathname of the executable which started the current Node.js process.

```javascript
console.log( EXEC_PATH );
// => <string>
```

</section>

<!-- /.usage -->

<section class="notes">

## Notes

-   In browser environments and environments other than Node.js, the absolute pathname of the executable is `null`.

</section>

<!-- /.notes -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var EXEC_PATH = require( '@stdlib/process-exec-path' );

if ( EXEC_PATH ) {
    console.log( 'Executable: %s', EXEC_PATH );
} else {
    console.log( 'Not running in Node.js.' );
}
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

[npm-image]: http://img.shields.io/npm/v/@stdlib/process-exec-path.svg
[npm-url]: https://npmjs.org/package/@stdlib/process-exec-path

[test-image]: https://github.com/stdlib-js/process-exec-path/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/process-exec-path/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/process-exec-path/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/process-exec-path?branch=main

[dependencies-image]: https://img.shields.io/david/stdlib-js/process-exec-path
[dependencies-url]: https://david-dm.org/stdlib-js/process-exec-path/main

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/process-exec-path/main/LICENSE

</section>

<!-- /.links -->