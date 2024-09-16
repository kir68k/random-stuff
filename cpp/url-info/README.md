<h1 align="center"><i>url-info</i></h1>

## What this
url-info is a simple C++ project/learning exercise which outputs information about a specified URL, using [ada](https://ada-url.com/).

## How to build
This project uses Nix + meson for compilation

### Dependencies
#### Using Nix
- Nix
    - Requires enabled flake support

#### Native meson
- ada
- boost
- meson
- pkg-config
- cmake
    - CMake is required for finding `ada`, pkg-config does not work.

### Building
#### Using nix
Simply run the following commands from this directory:
```bash
$ nix build
```
You can then use `./result/bin/url-info`.

#### Using native meson
Run the following commands from this directory:
```bash
meson setup build && cd build
ninja
```
You can then use `./url-info` from the build directory.

### Installing
WIP.
