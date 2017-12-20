# Memory64 for Nintendo 64

Memory game similar to [Simon](https://en.wikipedia.org/wiki/Simon_(game)) for N64,
design of the game is based on the N64 controller layout.

Support for Rumble Pak :D

| Main Menu | Game Screen |
| --------- | ----------- |
| ![main_menu](./screenshots/main_menu.png?raw=true) | ![game_screen](./screenshots/game_screen.png?raw=true) |


## Installation

[Download](./Memory64.z64?raw=true) or compile the ROM file and load it as
you would any other N64 ROM.

This ROM file has been tested to work on real Nintendo 64 hardware using the
[EverDrive-64 by krikzz](http://krikzz.com/). It should also work with
[64drive by retroactive](http://64drive.retroactive.be/).

This ROM file is only known to work on low-level, high-accuracy Nintendo 64
emulators such as [CEN64](https://cen64.com/) or [MAME](http://mamedev.org/)
due to the use of [libdragon](https://dragonminded.com/n64dev/libdragon/)
instead of the proprietary SDK used by official licensed Nintendo software.


## Building

In order to build you will need the following open-source software installed:

 * [libdragon development toolchain](https://github.com/DragonMinded/libdragon)
 * [`sox` command line audio conversion tool](http://sox.sourceforge.net/)

Run `make` to produce the `FlappyBird.z64` ROM file from this source tree.

You can run `make docker` to use [Docker](https://docker.com).

## Thanks

Thanks to [Christopher Bonhage](https://github.com/meeq) for his work on [FlappyBird-N64](https://github.com/meeq/FlappyBird-N64), where I drew most of my inspiration.