# Nero Linux 4 (Nero Burning ROM) for Void Linux

![nero-linux-4 0 0 0_1](https://github.com/MechDR/nero-linux-4-for-void-linux/assets/45944962/eec901f8-ae0e-4539-97da-a69f3a05c6ab)

This is a port of the (now discontinued) Nero Burning ROM for Linux. Ahead Software AG (now Nero AG) made this Linux port of Nero Burning ROM about 20 years ago, with this version (the last one) being released in 2010. There are other burning applications out here, sure, but some of us like the look and feel of Nero Burning ROM, so even though this is a 13 year old piece of software, some might still like to use it. It still works on modern distros, and (of course, tested) in Void Linux.

## How do I install it?

You either clone this repo and copy the `srcpkgs` directory in the `void-packages` directory and build with xbps-src (`./xbps-src pkg nero-linux`), or you download the packaged version I made from the releases page and point xbps-install to install from a local repository (`sudo xbps-src --repository /path/to/extracted/files nero-linux`). Both i686 (x86) and x86_64 (x64) versions are packaged. No other architectures are supported unfortunately.
