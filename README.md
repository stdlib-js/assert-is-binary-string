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

# isBinaryString

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Test if a value is a binary string.



<section class="usage">

## Usage

```javascript
import isBinaryString from 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-is-binary-string@esm/index.mjs';
```

#### isBinaryString( value )

Tests if a `value` is a binary `string`; i.e., a character sequence of `1`'s and `0`'s.

```javascript
var bool = isBinaryString( '1000101' );
// returns true

bool = isBinaryString( 'beep' );
// returns false

bool = isBinaryString( '' );
// returns false
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import isBinaryString from 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-is-binary-string@esm/index.mjs';

var bool = isBinaryString( '1' );
// returns true

bool = isBinaryString( '0' );
// returns true

bool = isBinaryString( '101010101001' );
// returns true

bool = isBinaryString( '' );
// returns false

bool = isBinaryString( 'beep' );
// returns false

bool = isBinaryString( null );
// returns false

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

-   <span class="package-name">[`@stdlib/assert-is-string`][@stdlib/assert/is-string]</span><span class="delimiter">: </span><span class="description">test if a value is a string.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

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

[npm-image]: http://img.shields.io/npm/v/@stdlib/assert-is-binary-string.svg
[npm-url]: https://npmjs.org/package/@stdlib/assert-is-binary-string

[test-image]: https://github.com/stdlib-js/assert-is-binary-string/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/assert-is-binary-string/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/assert-is-binary-string/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/assert-is-binary-string?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/assert-is-binary-string.svg
[dependencies-url]: https://david-dm.org/stdlib-js/assert-is-binary-string/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[cli-section]: https://github.com/stdlib-js/assert-is-binary-string#cli
[cli-url]: https://github.com/stdlib-js/assert-is-binary-string/tree/cli
[@stdlib/assert-is-binary-string]: https://github.com/stdlib-js/assert-is-binary-string/tree/main

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/assert-is-binary-string/tree/deno
[umd-url]: https://github.com/stdlib-js/assert-is-binary-string/tree/umd
[esm-url]: https://github.com/stdlib-js/assert-is-binary-string/tree/esm
[branches-url]: https://github.com/stdlib-js/assert-is-binary-string/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/assert-is-binary-string/main/LICENSE

[standard-streams]: https://en.wikipedia.org/wiki/Standard_streams

[mdn-regexp]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions

<!-- <related-links> -->

[@stdlib/assert/is-string]: https://github.com/stdlib-js/assert-is-string/tree/esm

<!-- </related-links> -->

</section>

<!-- /.links -->
