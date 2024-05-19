# Product Engineering Dojo book [![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)](https://opensource.org/license/mpl-2-0/)

A tale from the [Pet-Clinic multiverse](https://dxc-technology.github.io/about-pe-dojo/).

[![GitHub Super-Linter](https://github.com/tom-halpin/pe-dojo-book/actions/workflows/linter.yml/badge.svg)](https://github.com/marketplace/actions/super-linter)

## Introduction

This repository holds the Second Edition of an open-sourced book providing an Introduction to Product Engineering.

It is intended for anyone working in an organization that has or is embarking on a Product Engineering journey.

The first edition of the [Introduction to Product Engineering](https://github.com/dxc-technology/ebook-pe-dojo)s book was based on the Product Engineering Dojo from [DXC Technology](https://www.dxc.com) which provided an interactive Product Engineering training course.

## Content

The book includes **4** chapters and an assessment:

* Welcome
* Introduction to Product Engineering
* Design Thinking
* Getting Started
* Assessment

## Download

To download a copy of the book use one of the following links:

* [Light mode](https://github.com/tom-halpin/pe-dojo-book/blob/main/export/product-engineering-light.pdf)

* [Dark mode](https://github.com/tom-halpin/pe-dojo-book/blob/main/export/product-engineering-dark.pdf)

## book (PDF) Generation Tool

### Ibis

The project uses [Ibis](https://github.com/themsaid/ibis/) which is licensed under the [MIT License](https://github.com/themsaid/ibis/blob/master/LICENSE.md). [Ibis](https://github.com/themsaid/ibis/) is a PHP tool that enables the creation of eBooks from Markdown.

### Light Mode

To generate the [Light mode](https://github.com/tom-halpin/pe-dojo-book/blob/main/export/product-engineering-light.pdf) version of the book:

```bash
ibis build
```

### Dark Mode

To generate the [Dark mode](https://github.com/tom-halpin/pe-dojo-book/blob/main/export/product-engineering-dark.pdf) version of the book:

```bash
ibis build dark
```

## Links

* [Introduction to Product Engineering - First Edition](https://github.com/dxc-]technology/ebook-pe-dojo)
* [Ibis](https://github.com/themsaid/ibis/)

## Contributing

We :heart: contributions.

Please review the [Contributing Guide](CONTRIBUTING.md) before submitting a pull request.
