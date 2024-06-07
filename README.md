# Product Engineering Dojo book [![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)](https://opensource.org/license/mpl-2-0/)

A tale from the Pet-Clinic multiverse.

[![GitHub Super-Linter](https://github.com/tom-halpin/pe-dojo-book/actions/workflows/linter.yml/badge.svg)](https://github.com/marketplace/actions/super-linter)

## Introduction

This repository holds the Second Edition of an open-sourced book **Product Engineering An Introduction** providing an introduction to Product Engineering.

It is intended for anyone working in an organization that has or is embarking on a Product Engineering journey.

The first edition of the [Product Engineering An Introduction](https://github.com/dxc-technology/ebook-pe-dojo)s book was based on the **Product Engineering Dojo** from [DXC Technology](https://www.dxc.com). The **Product Engineering Dojo** provided an online interactive Product Engineering training course.

## Content

The book includes **5** chapters and an assessment:

* Welcome
* Introduction to Product Engineering
* Design Thinking
* Getting Started
* Afterword
* Assessment

## Download

To download a copy of the book use one of the following links:

* [Light mode](https://github.com/tom-halpin/pe-dojo-book/blob/main/export/product-engineering-light.pdf)

* [Dark mode](https://github.com/tom-halpin/pe-dojo-book/blob/main/export/product-engineering-dark.pdf)

## book (PDF) Generation Tool

### Ibis

The project uses [Ibis](https://github.com/themsaid/ibis/) which is licensed under the [MIT License](https://github.com/themsaid/ibis/blob/master/LICENSE.md). [Ibis](https://github.com/themsaid/ibis/) is a PHP tool that enables the creation of eBooks from Markdown. [Ibis](https://github.com/themsaid/ibis/) aims to simplify the eBook creation process by allowing the writers to focus on their content by providing the functionality required to convert that content into an eBook.

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

* [Product Engineering An Introduction - First Edition](https://github.com/dxc-technology/ebook-pe-dojo)
* [Ibis](https://github.com/themsaid/ibis/)

## Contributing

We :heart: contributions.

Please review the [Contributing Guide](CONTRIBUTING.md) before submitting a pull request.
