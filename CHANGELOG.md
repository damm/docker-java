## v0.00

Initial version

## v0.01

Include `/etc/fstab` and `/etc/mtab`

## v0.02

Hold the packages `initramfs` `mountall` `initscripts` and `udev` as they break int he upgrade
Make `/etc/mtab` actually a symlink of `/proc/self/mounts`
