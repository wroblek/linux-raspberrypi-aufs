linux-raspberrypi-aufs
======================

Aufs (Another UnionFS) friendly Raspberry Pi kernel.

Usage
----------------------

Copy modules to `/usr/lib/modules`.
Append `rwfs=tmpfs` to `cmdline.txt` and `kernel=kernel_aufs.img` to `config.txt`.
