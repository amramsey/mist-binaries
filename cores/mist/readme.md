Atari ST core for the MIST board
================================

In order to use this core you need to put it under the name core.rbf onto
the SD card. 

You also need a tos rom image. It's preferred to use a TOS 2.06 image
from e.g. [here](http://www.atariworld.org/tos-rom/). The tos rom
image must be named tos.img and has to be placed in the SD cards root
directory just like the core itself. Emutos is also supported, but is
not recommended due to its limited game compatibility.

To speed up booting a floppy disk image should also be present. Just
put the [demo
disk](https://github.com/mist-devel/mist-binaries/raw/master/cores/mist/disk_a.st)
also into the root of the SD card and the system will boot into the
desktop imediately.

To use the Atari ST system font for the MISTs first boot messages the
[Atari ST system font](https://github.com/mist-devel/mist-binaries/raw/master/cores/mist/system.fnt)
may also be copied into the cards root.

Other floppy disk images in .ST format can be selected in the OSD
(open with F12).

History
-------

* [core_181017.rbf](https://github.com/mist-devel/mist-binaries/raw/master/cores/mist/core_181017.rbf)
  - Make ym2149 i/o bidirectional. Fixing some games using the printer port to connect two more joysticks

* [core_180908.rbf](https://github.com/mist-devel/mist-binaries/raw/master/cores/mist/old/core_180908.rbf)
  - YPbPr component video support

* [core_160129.rbf](https://github.com/mist-devel/mist-binaries/raw/master/cores/mist/old/core_160129.rbf)
  - 68020 bitfield fixes and barrel shifter 

* [core_151123.rbf](https://github.com/mist-devel/mist-binaries/raw/master/cores/mist/old/core_151123.rbf)
  - STE/YM audio mixer adjustments. Fixes Anarcho Ride

* [core_151122.rbf](https://github.com/mist-devel/mist-binaries/raw/master/cores/mist/old/core_151122.rbf)
  - CPU illegal instruction fix. Fixes MAGIC 6.20 ROM
