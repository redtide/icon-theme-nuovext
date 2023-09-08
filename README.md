# nuoveXT

A freedesktop icon theme using nuoveXT2.2 icon set,
a lxde-icon-theme modification.

## Installation

```sh
cmake -B build -D CMAKE_INSTALL_PREFIX=/usr
cmake --build build --verbose
DESTDIR=$(pwd)/package cmake --install build
```
