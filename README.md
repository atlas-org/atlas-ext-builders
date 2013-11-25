atlasoff-builders
=================

``atlasoff-builders`` is a `hwaf-worch` package to build and install ``ATLAS`` externals.

## Installation

Is as easy as:

```sh
$ git clone git://github.com/atlas-org/atlasoff-builders
$ cd atlas-ext-builders
$ hwaf init && hwaf setup
$ hwaf configure build
```

To pick-up an already configured toolchain (_e.g._ ``LCG-65``):
```sh
$ cd atlasoff-builders
$ hwaf init
$ hwaf setup -p /path/to/installed/lcg-65
$ hwaf configure
# NOTE: hwaf shell won't be needed in a more recent hwaf version
$ hwaf shell
$ hwaf build
```
