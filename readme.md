# Awesome Cross-Platform Node.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome [libraries](#libraries) and [applications](#applications) for writing and testing code that works on Windows and Unix-like platforms.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Table of Contents

- [Resources](#resources)
- [Known Issues](#known-issues)
- [Online Tools](#online-tools)
- [Applications](#applications)
  - [Virtualization](#virtualization)
  - [Development Environment](#developer-environment)
- [Libraries](#libraries)
- [Support](#support)
- [Contributing](#contributing)

## Resources

- [Microsoft Open Technologies](https://github.com/MSOpenTech) - Windows ports of non-Microsoft technologies.
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - Tips, tricks, and resources for working with Node.js on Microsoft platforms.
- [Writing Cross-Platform Node.js](http://shapeshed.com/writing-cross-platform-node/) - a great tutorial covering many common issues that arise when writing cross-platform code: path creation, script execution, newline characters.
- [Portable Node.js guide](https://github.com/ehmicky/portable-node-guide) - Practical guide on how to write portable/cross-platform Node.js code

## Known Issues

- [cmd.exe unicode woes](https://github.com/nodejs/node-v0.x-archive/issues/7940) - by default, cmd.exe does not display unicode characters on Windows.
- [spawn issues](https://github.com/nodejs/node-v0.x-archive/issues/2318) - `child_process.spawn()` behavior is not consistent between Windows and Linux.
- [node-gyp on Windows](https://github.com/nodejs/node-gyp/issues/629) - it can be quite painful to compile native modules on Windows.
- [stdio issues on v0.10.x](https://github.com/nodejs/node-v0.x-archive/issues/3584) - a race condition in stdio lead to confusing terminal output when testing on Windows prior to Node v0.11.12.
- [exec() behavior between shells](https://github.com/isaacs/spawn-wrap#contracts-and-caveats) - depending on the shell being used, e.g., bash vs. dash, `child_process.exec()` has inconsistent exit behavior.

## Online Tools

- [AppVeyor](http://www.appveyor.com/) - Continuous integration service for Windows. Free tiers are available for OSS projects.

## Applications

### Virtualization

- [ievms](https://github.com/xdissent/ievms) - Automated installer for the free virtual machine images that Microsoft provides for testing on multiple versions of IE. These images can be useful for cross-platform testing various technologies, however make sure you read and understand Microsofts' licensing.
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads) - General purpose software for running x86 virtual machines.

### Development Environment

- [Atom](https://github.com/atom/atom/releases/latest) - A cross-platform, full-featured, hackable text editor.
- [Node.js](https://nodejs.org/en/download/) - Node.js installer for various platforms.
- [MSOpenTech Redis](https://github.com/MSOpenTech/redis/releases/latest) - A build of Redis maintained by Microsoft Open Technologies.
- [nvm-windows](https://github.com/coreybutler/nvm-windows) - Manage multiple installations of Node.js on a Windows computer.

## Libraries

- [any-path](https://github.com/bcoe/any-path) - Use Windows and POSIX paths interchangeably when fetching values from an object.
- [is-windows](https://github.com/jonschlinkert/is-windows) - Detect whether the current platform is Windows.
- [rimraf](https://github.com/isaacs/rimraf) - Cross-platform `rm -rf`.
- [make-dir](https://github.com/sindresorhus/make-dir) - Cross-platform `mkdir -p`.
- [execa](https://github.com/sindresorhus/execa) - Cross-platform implementation of `child_process.{execFile,exec}`.
- [which](https://github.com/npm/node-which) - Cross-platform implementation of Unix's `which`.
- [user-home](https://github.com/sindresorhus/user-home) - Get the path to the user home directory. Cross-platform.
- [opn](https://github.com/sindresorhus/opn) - Opens stuff like websites, files, executables. Cross-platform.
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels with Windows fallbacks.
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows fallbacks.
- [del](https://github.com/sindresorhus/del) - Delete files and folders. Cross-platform.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. Cross-platform.
- [fkill](https://github.com/sindresorhus/fkill-cli) - Kill processes. Cross-platform.
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Improves the `fs` module, especially on Windows.
- [chokidar](https://github.com/paulmillr/chokidar) - Improved cross-platform file watching.
- [shelljs](https://github.com/shelljs/shelljs) - Cross-platform Unix shell commands.
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform.
- [cross-spawn](https://github.com/IndigoUnited/node-cross-spawn) - Cross-platform implementation of `child_process.spawn()`.
- [clipboardy](https://github.com/sindresorhus/clipboardy) - Cross-platform copy/paste.

## Support

If you found an error or would like to add more information, _don't hesitate_ to
[submit an issue on GitHub](../../issues).

Everyone is welcome regardless of personal background. We enforce a
[Code of conduct](CODE_OF_CONDUCT.md) in order to promote a positive and
inclusive environment.

## Contributing

This project was made with ❤️. The simplest way to give back is by starring and
sharing it online.

If the documentation is unclear or has a typo, please click on the page's `Edit`
button (pencil icon) and suggest a correction.

If you would like to help us fix an error or add more information, please check
our [guidelines](contributing.md). Pull requests are welcome!

Thanks goes to these wonderful people:

<!-- ALL-CONTRIBUTORS-LIST:START -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="https://twitter.com/benjamincoe"><img src="https://avatars3.githubusercontent.com/u/194609?v=4" width="100px;" alt="Benjamin E. Coe"/><br /><sub><b>Benjamin E. Coe</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=bcoe" title="Code">💻</a> <a href="#ideas-bcoe" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=bcoe" title="Documentation">📖</a></td><td align="center"><a href="https://twitter.com/ehmicky"><img src="https://avatars2.githubusercontent.com/u/8136211?v=4" width="100px;" alt="ehmicky"/><br /><sub><b>ehmicky</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=ehmicky" title="Code">💻</a> <a href="#ideas-ehmicky" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=ehmicky" title="Documentation">📖</a></td><td align="center"><a href="https://sindresorhus.com"><img src="https://avatars1.githubusercontent.com/u/170270?v=4" width="100px;" alt="Sindre Sorhus"/><br /><sub><b>Sindre Sorhus</b></sub></a><br /><a href="#ideas-sindresorhus" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://kentcdodds.com"><img src="https://avatars0.githubusercontent.com/u/1500684?v=4" width="100px;" alt="Kent C. Dodds"/><br /><sub><b>Kent C. Dodds</b></sub></a><br /><a href="#ideas-kentcdodds" title="Ideas, Planning, & Feedback">🤔</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->
