# Welcome to GZDoom!

[![Continuous Integration](https://github.com/ZDoom/gzdoom/actions/workflows/continuous_integration.yml/badge.svg)](https://github.com/ZDoom/gzdoom/actions/workflows/continuous_integration.yml)

## GZDoom is a modder-friendly OpenGL and Vulkan source port based on the DOOM engine

Copyright (c) 1998-2022 ZDoom + GZDoom teams, and contributors

Doom Source (c) 1997 id Software, Raven Software, and contributors

Please see license files for individual contributor licenses

Special thanks to Coraline of the EDGE team for allowing us to use her [README.md](https://github.com/3dfxdev/EDGE/blob/master/README.md) as a template for this one.

### Licensed under the GPL v3
##### https://www.gnu.org/licenses/quick-guide-gplv3.en.html
---
## How to build GZDoom in Void Linux
wget https://github.com/void-linux/void-packages/archive/refs/heads/master.zip -O void-packages.zip
unzip void-packages.zip
cd void-packages-master
./xbps-src binary-bootstrap
leafpad srcpkgs/gzdoom/template

add libvpx-devel in the makedepends, change the version to 4.8.2, save it, then remove the folder patches of gzdoom

./xbps-src pkg gzdoom
xgensum -i gzdoom
./xbps-src pkg gzdoom

## How to build GZDoom

To build GZDoom, please see the [wiki](https://zdoom.org/wiki/) and see the "Programmer's Corner" on the bottom-right corner of the page to build for your platform.

