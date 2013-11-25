atlas-ext-builders
=================

``atlas-ext-builders`` is a `hwaf-worch` package to build and install ``ATLAS`` externals.

## Installation

Is as easy as:

```sh
$ git clone git://github.com/atlas-org/atlas-ext-builders
$ cd atlas-ext-builders
$ hwaf init && hwaf setup
$ hwaf configure build
```

To pick-up an already configured toolchain (_e.g._ ``LCG-65``):
```sh
$ cd atlas-ext-builders
$ hwaf init
$ hwaf setup -p /path/to/installed/lcg-65
$ hwaf configure build
```
