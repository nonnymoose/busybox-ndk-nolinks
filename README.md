# busybox-ndk-nolinks
A Magisk module to install a busybox binary and nothing else

This Magisk module automatically detects the processor architecture of your device and creates the appropriate busybox binary in `/system/xbin`. **No symbolic links are created! If you want to use a busybox applet, you __must__ do** `busybox appletname`**! If you are looking for a busybox installer that installs each applet as a symbolic link for ease of use, you are looking for `busybox-ndk`!**

This module is based on and uses the binaries from @osm0sis's `busybox-ndk`. I give them credit for the binaries and the architecture-detector part of the Magisk installer; however, I created the install script for this module.

Check out their [repository](https://github.com/Magisk-Modules-Repo/busybox-ndk), [xda post](https://forum.xda-developers.com/showpost.php?p=64228091&postcount=420), and [xda user page](https://forum.xda-developers.com/member.php?u=4544860)!

@osmosis's donation page is [here](https://forum.xda-developers.com/donatetome.php?u=4544860).
