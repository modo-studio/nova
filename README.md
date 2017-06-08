nova
==================

<p align="left">
    <a href="https://travis-ci.org/pepibumur/nova">
        <img src="https://travis-ci.org/pepibumur/nova.svg?branch=master">
    </a>
    <a href="https://swift.org/package-manager">
        <img src="https://img.shields.io/badge/spm-compatible-brightgreen.svg?style=flat" alt="Swift Package Manager" />
    </a>
    <a href="https://twitter.com/pepibumur">
        <img src="https://img.shields.io/badge/contact-@pepibumur-blue.svg?style=flat" alt="Twitter: @pepibumur" />
    </a>
</p>

### Cartago file
A `cartago.yml` defines the structure of your project for Apple platforms, decoupling it from Xcode. In a Cartago file you can define things like:
- Source files.
- Type of product *(app, extension, framework...)*
- Test files.
- Dependencies with other cartago projects.

[Nova](https://github.com/carambalabs/nova) is a Swift library that provides tools for **parsing** and **validating** Cartago files.

### Motivation
Cartago files are used by [cartago](https://github.com/carambalabs/cartago), a command line tools that offers:
- Generation of Xcode projects.
- Building without using Xcode.
- ...

### Contribute

1. Git clone the repository `git@github.com:carambalabs/nova.git`.
2. Open `nova.xcodeproj`

### Example

```yml
// Cartagofile
type: app
source_files:
    - Sources/*.swift

````

## About

<img src="https://github.com/carambalabs/Foundation/blob/master/ASSETS/avatar_rounded.png?raw=true" width="70" />

This project is funded and maintained by [Caramba](http://caramba.io). We 💛 open source software!

Check out our other [open source projects](https://github.com/carambalabs/), read our [blog](http://blog.caramba.io) or say :wave: on twitter [@carambalabs](http://twitter.com/carambalabs).

## Contribute

Contributions are welcome :metal: We encourage developers like you to help us improve the projects we've shared with the community. Please see the [Contributing Guide](https://github.com/carambalabs/Foundation/blob/master/CONTRIBUTING.md) and the [Code of Conduct](https://github.com/carambalabs/Foundation/blob/master/CONDUCT.md).


### License

```
MIT License

Copyright (c) 2017 Cartago

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```