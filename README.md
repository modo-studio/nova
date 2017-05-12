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
A `cartago.yml` defines the structure of your project, decoupling it from Xcode. In a Cartago file you can define things like:
- Source files.
- Type of product *(app, extension, framework...)*
- Test files.
- Dependencies with other cartago projects.

[Nova](https://github.com/cartagoproject/nova) is a Swift library that provides tools for parsing and validating Cartago files.

### Motivation
Cartago files are used by [cartago](https://github.com/cartagoproject/cartago), a command line tools that offers:
- Generation of Xcode projects.
- Building without using Xcode.

### Contribute

1. Git clone the repository `git@github.com:cartagoproject/nova.git`.
2. Open `xcodeproj.xcodeproj`