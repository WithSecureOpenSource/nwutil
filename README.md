## Overview

nwutil is a C library for Linux-like operating systems that offers a
number of useful functions for networking.

## Building

nwutil uses [SCons][] and `pkg-config` for building.

Before building nwutil for the first time, run
```
git submodule update --init
```

To build nwutil, run
```
scons [ prefix=<prefix> ]
```
from the top-level nwutil directory. The optional prefix argument is a
directory, `/usr/local` by default, where the build system installs
nwutil.

To install nwutil, run
```
sudo scons [ prefix=<prefix> ] install
```

## Documentation

The header files under `include` contain detailed documentation.

[SCons]: https://scons.org/
