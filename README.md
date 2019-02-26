# ![logo][] Genume - *Graphical ENUMEration*

**Genume** is a Linux graphical user interface utility tool that serves as a means
of providing the user with a plethora of enumeration scripts.

[logo]: https://raw.githubcontent.com/CSD-FOSS-Team/genume/master/assets/logo.svg?sanitize=true

![build status][]
![python][]
![GPLv2][]
![Screenshot]

[build status]: https://img.shields.io/travis/CSD-FOSS-Team/genume.svg
[python]: https://img.shields.io/badge/python-3.3,%203.4,%203.5,%203.6,%203.7-blue.svg
[GPLv2]: https://img.shields.io/badge/license-GPLv2-lightgrey.svg
[screenshot]: httpsL//raw.githubcontent.com/CSD-FOSS-Team/genume/master/assets/screenshot_genume.png?sanitize=true

## New to Genume?

If you are new to Genume and would like to learn more, we recommend reviewing the [getting started] documentation.

[getting started]: https://github.com/CSD-FOSS-Team/genume/tree/master/docs/learning-genume

## Get Genume

You can download Genume's source code by
`mkdir <new-dir>`
`cd <new-dir>`
`git clone https://github.com/CSD-FOSS-Team/genume.git`

See [working with the Genume repository](https://github.com/CSD-FOSS-Team/genume/tree/master/docs/git) for more information.

Build with Python 3 and Gtk+3.

Start Genume by running `make` or `python3 -m genume`.

## Developing and Contributing

Please see the [Contribution Guide][] for how to develop and contribute.

[Contribution Guide]: https://github.com/CSD-FOSS-Team/genume/blob/master/.github/CONTRIBUTING.md

## Support

For support please see the [Support Section][].

[Support Section]: https://github.com/CSD-FOSS-Team/genume/tree/master/.github/SUPPORT.md

## Legal and Licensing

All files in this repository are Copyright (c) 2018 **genume author list**.

Code in this repository is licensed under the [GNU General Public License v2.0][], unless explicitly stated otherwise.

Data in this repository is licensed under the
[Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/), unless explicitly stated otherwise.

Documentation in this repository uses [Genume][]'s docs as a format template, which is licensed under the [MIT License][]

**genume author list** can be determined via `git shortlog -sne`.

[GNU General Public License v2.0]: https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html


[MIT License]: https://opensource.org/licenses/MIT

## Features

Genume utilizes a custom [protocol][] and [bash helpers][], which reinforces the core design idea of heavy modularity.
By default genume displays the collected information in a GUI,
but it can also export the enumeration in a wide range of various file formats.
Visit the [getting started] documentation.

[getting started]: https://github.com/CSD-FOSS-Team/genume/tree/master/docs/learning-genume


## Install

TODO: #22

## Building the Repository

TODO: ?

### Build Genume on Linux

This guide will walk you through building Genume on Linux.
We'll start by showing how to set up your environment from scratch.

### Environment

We strive to establish Genume as a distribution-independant tool. 

#### Git Setup

Using Git requires it to be set up correctly;
refer to the [Working with the Genume Repository](../git/README.md),
[README](../../README.md), and [Contributing Guidelines](../../.github/CONTRIBUTING.md).

**This guide assumes that you have recursively cloned the Genume repository and `cd`ed into it.**