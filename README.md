atlasext-builders
=================

``atlasext-builders`` is a `hwaf-worch` package to build and install ``ATLAS`` externals.

## Installation

Is as easy as:

```sh
$ git clone git://github.com/atlas-org/atlasext-builders
$ cd atlasext-builders
$ hwaf init && hwaf setup
$ hwaf configure build
```

To pick-up an already configured toolchain (_e.g._ ``LCG-65``):
```sh
$ cd atlasext-builders
$ hwaf init
$ hwaf setup -p /path/to/installed/lcg-65
$ hwaf configure
# NOTE: hwaf shell won't be needed in a more recent hwaf version
$ hwaf shell
$ hwaf build
```

### Profile for ASG

To build the externals for ``ASG`` one can instead run the
``suite-asg`` suite:

```sh
$ git clone git://github.com/atlas-org/atlasext-builders
$ cd atlasext-builders
$ hwaf init && hwaf setup
$ hwaf configure --hwaf-worch-config=suite-asg.cfg
$ hwaf
```
