# abs-ijobstat-build
Utilities for testing and building of the [abs-ijobstat](https://github.com/kulhanek/abs-ijobstat) package.

## Building and Installation

### Testing Mode
```bash
$ git clone --recursive https://github.com/kulhanek/abs-ijobstat-build.git
$ cd abs-ijobstat-build
$ ./build-utils/00.init-links.sh
$ ./01.pull-code.sh
$ ./04.build-inline.sh      # build the code inline in src/
```

### Production Build
```bash
$ git clone --recursive https://github.com/kulhanek/abs-ijobstat-build.git
$ cd abs-ijobstat-build
$ ./build-utils/00.init-links.sh
$ ./01.pull-code.sh
$ ./10.build-final.sh       # install dir: /opt/abs-ijobstat/4.0
```




