# [KISS Linux](https://k1ss.org/) for aarch64

This is a repository containing an unofficial port of [KISS Linux](https://k1ss.org/) to the [aarch64](https://en.wikipedia.org/wiki/ARM_architecture#AArch64) [Pinebook Pro](https://www.pine64.org/pinebook-pro/) platform.

![KISS Linux aarch64 screenshot](https://raw.githubusercontent.com/jedavies-dev/kiss-aarch64/master/screenshot3.png "KISS Linux aarch64")

```Work in progress```


# Installation
You can install the [root tarball](https://github.com/jedavies-dev/kiss-aarch64/releases/download/0.1/kiss-chroot.tar.xz) from another distro, same as on x86_64.  See https://k1ss.org/install for general installation details.

Booting involves either:
1) Writing the ATF and u-boot to an SD/MMC drive and installing the tarball there
2) Altering another distro's boot.txt to point to a drive containing the KISS root.

Next on the todo list:
 - Confirm all packages build, patch where required.
 - Provide detailed instructions on how to create a bootable device.
 - Create bootable image file for flashing to sd/mmc as an alternative installation method.
 - Provide firefox-bin for convenience.
 - More docs (separate website?).
 - Provide instructions on how to run without any binary blobs (it is possible!).
 
