# makerlisp-cpm-00
cp/m for makerlisp ez80 computer with fat file system

This an alpha of alphas. That implements CP/M on the z20x ez80 computer.

This software is slow to read and write the sd card and executes its bios code out of flash rom and is therefore even slower.
Currently it only uses uart0 for a console so you will need to add a serial to usb converter or a ttl to rs232 level shifter
via the expansion bus.

The baud is 57600. If you want to help migrate the console to the internal display and ps2 keyboard, let me know.
