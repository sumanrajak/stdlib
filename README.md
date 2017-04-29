
<div class="image" align="center">
    <img src="https://cdn.rawgit.com/stdlib-js/stdlib/6746dfdc6e031f695fc56fbefdb16e752c4d2716/docs/assets/logo_header.png" alt="stdlib logo">
    <br>
</div>

---

# stdlib

> A standard library for JavaScript and Node.js.

Stdlib is a collection of robust, high performance libraries for numeric computing, streams, and more. This is the GitHub repository of stdlib source code and documentation.

If you are interested in developing stdlib, see the [development guide][stdlib-development].


## Prerequisites

Running stdlib __requires__ the following prerequisites:

* [Node.js][node-js]: JavaScript runtime (version `>= 0.10`)
* [npm][npm]: package manager (version `> 2.7.0`; if Node `< 1.0.0`, version `> 2.7.0` and `< 4.0.0`)

Most functionality in stdlib is implemented __exclusively__ in JavaScript; however, some implementations try to capture performance benefits by using native bindings. While __not__ required to run stdlib, as __every__ stdlib implementation has a JavaScript fallback, the following dependencies are __required__ for building native add-ons, including linking to BLAS and LAPACK libraries:

* [GNU make][gnu-make]: development utility and task runner
* [gcc &amp; g++][gcc] or [Clang][clang]: C/C++ compilation and linking (g++ version `>= 4.8`; clang version `>= 3.5`, Xcode version `>=4.4` on OS X)
* [gfortran][gfortran]: Fortran compilation and linking (version `>= 4.8`)

While __not__ required to run stdlib, the following dependencies are __required__ for automatically downloading vendor libraries:

* [curl][curl], [wget][wget], or [fetch][fetch] (FreeBSD): utilities for downloading remote resources

The following vendor libraries can be automatically downloaded and compiled from source using `make`:

* [OpenBLAS][openblas]: optimized BLAS library


## Installation

To install stdlib as a library or application dependency,

``` bash
$ npm install @stdlib/stdlib
```

Otherwise, to install as a system library, follow the [download][stdlib-development], [configuration][stdlib-development], and [installation][stdlib-development] instructions as described in the [development guide][stdlib-development].


---

## Contributing

See the [contributing guidelines][stdlib-contributing].


## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2017. The Stdlib [Authors][stdlib-authors].


<!-- <badges> -->

---

## Status

[![stability-experimental][stability-image]][stability-url]

#### Version

[![git tag][tag-image]][tag-url] [![NPM version][npm-image]][npm-url] [![Node.js version][node-image]][node-url]

#### Build

<!-- TODO: distinguish between Linux and Windows code coverage -->

<!--lint disable table-pipe-alignment-->

| OS | Build (master) | Coverage (master) | Build (develop) | Coverage (develop) |
| --- | --- | --- | --- | --- |
| Linux/OS X | [![Linux/OS X build status (master)][build-image-master]][build-url-master] | [![coverage (master)][coverage-image-master]][coverage-url-master] | [![Linux/OS X build status (develop)][build-image-develop]][build-url-develop] | [![coverage (develop)][coverage-image-develop]][coverage-url-develop] |
| Windows | [![Windows build status (master)][windows-build-image-master]][windows-build-url-master] | [![coverage (master)][coverage-image-master]][coverage-url-master] | [![Windows build status (develop)][windows-build-image-develop]][windows-build-url-develop] | [![coverage (develop)][coverage-image-develop]][coverage-url-develop] |

<!--lint enable table-pipe-alignment-->


#### Dependencies

[![Dependencies][dependencies-image]][dependencies-url] [![DevDependencies][dev-dependencies-image]][dev-dependencies-url]


#### Community

[![Chat][chat-image]][chat-url]

<!-- </badges> -->


<section class="links">

[stability-image]: https://img.shields.io/badge/stability-experimental-orange.svg
[stability-url]: https://github.com/stdlib-js/stdlib

[npm-image]: https://img.shields.io/npm/v/@stdlib/stdlib.svg
[npm-url]: https://npmjs.org/package/@stdlib/stdlib

[tag-image]: https://img.shields.io/github/tag/stdlib-js/stdlib.svg
[tag-url]: https://github.com/stdlib-js/stdlib/tags

[node-image]: https://img.shields.io/node/v/@stdlib/stdlib.svg
[node-url]: https://github.com/@stdlib-js/stdlib

[build-image-master]: https://img.shields.io/travis/stdlib-js/stdlib/master.svg
[build-url-master]: https://travis-ci.org/stdlib-js/stdlib

[build-image-develop]: https://img.shields.io/travis/stdlib-js/stdlib/develop.svg
[build-url-develop]: https://travis-ci.org/stdlib-js/stdlib

<!-- FIXME: shields.io AppVeyor badges do not seem to work -->

[windows-build-image-master]: https://ci.appveyor.com/api/projects/status/github/stdlib-js/stdlib?branch=master&svg=true
[windows-build-url-master]: https://ci.appveyor.com/api/projects/status/github/stdlib-js/stdlib?branch=master&svg=true

[windows-build-image-develop]: https://ci.appveyor.com/api/projects/status/github/stdlib-js/stdlib?branch=develop&svg=true
[windows-build-url-develop]: https://ci.appveyor.com/api/projects/status/github/stdlib-js/stdlib?branch=develop&svg=true

[coverage-image-master]: https://img.shields.io/codecov/c/github/stdlib-js/stdlib/master.svg
[coverage-url-master]: https://codecov.io/github/stdlib-js/stdlib/branch/master

[coverage-image-develop]: https://img.shields.io/codecov/c/github/stdlib-js/stdlib/develop.svg
[coverage-url-develop]: https://codecov.io/github/stdlib-js/stdlib/branch/develop

[dependencies-image]: https://img.shields.io/david/stdlib-js/stdlib/develop.svg
[dependencies-url]: https://david-dm.org/stdlib-js/stdlib/develop

[dev-dependencies-image]: https://img.shields.io/david/dev/stdlib-js/stdlib/develop.svg
[dev-dependencies-url]: https://david-dm.org/stdlib-js/stdlib/develop#info=devDependencies

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[gnu-make]: https://www.gnu.org/software/make
[curl]: http://curl.haxx.se/
[wget]: http://www.gnu.org/software/wget
[fetch]: http://www.freebsd.org/cgi/man.cgi?fetch%281%29
[node-js]: https://nodejs.org/en/
[npm]: https://www.npmjs.com/

[gcc]: http://gcc.gnu.org/
[clang]: http://clang.llvm.org/
[gfortran]: https://gcc.gnu.org/fortran/

[openblas]: https://github.com/xianyi/OpenBLAS

[stdlib-contributing]: https://github.com/stdlib-js/stdlib/blob/develop/CONTRIBUTING.md
[stdlib-development]: https://github.com/stdlib-js/stdlib/blob/develop/docs/development.md

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors
[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/stdlib/develop/LICENSE

</section>

<!-- /.links -->
