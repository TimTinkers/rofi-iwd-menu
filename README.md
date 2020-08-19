# rofi-iwd-menu
This repository contains a simple script for managing a [Rofi](https://github.com/davatorium/rofi)-based menu that can control WiFi connections via [iwd](https://wiki.archlinux.org/index.php/Iwd). This is a port of [Zach Baylin](https://github.com/zbaylin)'s work on [rofi-wifi-menu](https://github.com/zbaylin/rofi-wifi-menu) which borrows heavily from the source material.

## Usage
Download and run the `rofi-wifi-menu.sh` script. The script accepts additional, optional parameters: `rofi-wifi-menu.sh [device] [position] [y-offset] [x-offset]`.
- `device`: the iwd device to establish the WiFi connection on; defaults to `wlan0`.
- `position`: a layer position; defaults to `0`. You probably never need to change this.
- `y-offset`: a y-offset for controlling menu rendering location; defaults to `0`.
- `x-offset`: an x-offset for controlling menu rendering location; defaults to `0`.

## Special Thanks
Special thanks is owed to the following organizations, projects, and people without whose work this repository would not be possible.
- [Zach Baylin](https://github.com/zbaylin) whose [rofi-wifi-menu](https://github.com/zbaylin/rofi-wifi-menu) served as a foundation.
- all of the diligent maintainers of the [Arch Linux Wiki](https://wiki.archlinux.org/), the greatest learning resource I've ever found in customizing my system.
