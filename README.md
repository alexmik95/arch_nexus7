# INSTALL ARCHLINUX ON NEXUS 7 (GROUPER) WITH MULTIROM

This guide target to native install archlinux on nexus 7 2012 with multirom as bootloader:

1. Download latest release for nvidia trimslice from archlinux ARM repository.
2. Organize all files like a .mrom multirom installation package:
  archlinuxN7.mrom -> /rom/root.tar.gz /root-dir/rom_info.txt /post_install/01_copyfiles.sh /manifest.txt
  It's a simple zip archive renamed .mrom to be installed in twrp recovery.
3. Copy the archive on system memory
4. Reboot in recovery e go in multirom option, add rom and select the .mrom file path.
5. Reboot system and boot in archlinux fresh installed.

At present time it install and boot but fail initial check and reboot system

### TO DO: find a method to generate intrd.img and vmlinuz.img

credits to tassadar for multirom project
