<h1 align="center">
  dmenu
</h1>

## What's special about this build?
This custom build include the necessary
to support emoji & custom theming via [Pywal](https://github.com/dylanaraps/pywal).

## What is dmenu?
dmenu is an efficient dynamic menu for X.


## Requirements
In order to build dmenu you need the Xlib header files.


## Installation
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):
```shell
make clean install
```

## Running dmenu
See the man page for details.
