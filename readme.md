# Awesome Cross-Platform Node.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome [libraries](#libraries) and [developer tools](#developer-tools) for writing and testing code that works on Windows and Unix-like platforms.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Table of Contents

- [Resources](#resources)
- [Continuous Integration](#continuous-integration)
- [Applications](#applications)
  - [Virtualization](#virtualization)
  - [Development Environment](#developer-environment)
- [Libraries](#libraries)

## Resources

- [Microsoft Open Technologies](https://github.com/MSOpenTech) - Windows ports of non-Microsoft technologies.
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - Tips, tricks, and resources for working with Node.js on Microsoft platforms.

## Continuous Integration

- [AppVeyor](http://www.appveyor.com/) - Continuous integration service for Windows. Free tiers are available for OSS projects.

## Applications

### Virtualization

- [ievms](https://github.com/xdissent/ievms) - Automated installer for the free virtual machine images that Microsoft provides for testing on multiple versions of IE. These images can be useful for cross-platform testing various technologies, however make sure you read and understand Microsofts' licensing.
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads) - General purpose software for running x86 virtual machines.

### Development Environment

- [Atom](https://github.com/atom/atom/releases/latest) - A cross-platform, full-featured, hackable text editor.
- [Node.js](https://nodejs.org/en/download/) - Node.js installer for various platforms.
- [MSOpenTech Redis](https://github.com/MSOpenTech/redis/releases/latest) - A build of Redis maintained by Microsoft Open Technologies.

## Libraries

- [any-path](https://github.com/bcoe/any-path) - Use Windows and POSIX paths interchangeably when fetching values from an object.  
- [is-windows](https://github.com/jonschlinkert/is-windows) - Detect whether the current platform is Windows.
- [rimraf](https://github.com/isaacs/rimraf) - Cross-platform rm -rf.
- [mkdirp](https://github.com/substack/node-mkdirp) - Cross-platform mkdir -p.
- [win-spawn](https://github.com/ForbesLindesay/win-spawn) - Cross-platform implementation of child_process.spawn().
- [which](https://github.com/npm/node-which) - Cross-platform implementation of unix's which.
