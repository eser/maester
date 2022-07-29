# 📜 [maester](https://github.com/eserozvataf/maester)

[![build status][build-image]][build-url]
[![npm version][npm-image]][npm-url]
[![npm download][download-image]][npm-url]
[![dependencies][dep-image]][dep-url]
[![coverage status][coverage-image]][coverage-url]
[![license][license-image]][license-url]


## Update (July 2022)

DEPRECATED in favor of [hex](https://github.com/eserozvataf/hex).
See https://github.com/eserozvataf/hex for details.


## What is the Maester?

This project is designed for being responsible of all exception handling and logging features that a JavaScript application needs.


## Why Maester?

I like standartization in general concepts like error handling and logging. I have several node.js and browser application projects and most of the time I try to keep my code design similar, portable and shareable for applicability to other scenerios. Maester is the one of the products that I have developed with this mindset.

As an exception handling and logging library,

- Delivers base exception classes,
- Provides a logging interface can be called in any module,
- Event-based system can be easily subscribed by other parties,
- Built-in and extensible loggers/appenders can be attached or detached at any time,
- Customizable severity levels,
- Formatters for log entries,
- Multiplatform support for browsers and node.js,


## Quick start

Execute `npm install maester` to install maester and its dependencies into your project directory.


## Usage

For example, to append a new item to an existing array:

```js
import maester from 'maester';

maester.info('An information message');
maester.error('An error occurred', { user: localStorage.userId });
```


## Todo List

- FileLogger, RollingFileLogger, StreamLogger etc.
- Exception formatters
- DateTime entries
- Custom severities for each logger
- Events for handling exceptions

See [GitHub Projects](https://github.com/eserozvataf/maester/projects) for more.


## Requirements

* node.js (https://nodejs.org/)


## License

Apache 2.0, for further details, please see [LICENSE](LICENSE) file


## Contributing

See [contributors.md](contributors.md)

It is publicly open for any contribution. Bugfixes, new features and extra modules are welcome.

* To contribute to code: Fork the repo, push your changes to your fork, and submit a pull request.
* To report a bug: If something does not work, please report it using [GitHub Issues](https://github.com/eserozvataf/maester/issues).


## To Support

[Visit my patreon profile at patreon.com/eserozvataf](https://www.patreon.com/eserozvataf)


[build-image]: https://travis-ci.org/eserozvataf/maester.svg?branch=master
[build-url]: https://travis-ci.org/eserozvataf/maester
[npm-image]: https://img.shields.io/npm/v/maester.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/maester
[download-image]: https://img.shields.io/npm/dt/maester.svg?style=flat-square
[dep-image]: https://img.shields.io/david/eserozvataf/maester.svg?style=flat-square
[dep-url]: https://github.com/eserozvataf/maester
[coverage-image]: https://codecov.io/gh/eserozvataf/maester/branch/master/graph/badge.svg
[coverage-url]: https://codecov.io/gh/eserozvataf/maester
[license-image]: https://img.shields.io/npm/l/maester.svg?style=flat-square
[license-url]: https://github.com/eserozvataf/maester/blob/master/LICENSE
