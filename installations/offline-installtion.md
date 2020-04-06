---
description: This page directs you how to make an offline installtion of any distro.
---

# Offline Installtion

Choose any distro and click on **Download Offline** to download the distro.

Once the distro is downloaded open Termux and follow the given commands:

* Type `termux-setup-storage` and enable Storage permission to Termux
* Below is the list of each Offline distro. Choose and run the command according to your downloaded distro

```text
Ubuntu: cp /sdcard/Download/ubuntu.tar.gz && cd ~ && tar xf ubuntu.tar.gz && rm -rf ubuntu.tar.gz


Ubuntu19: cp /sdcard/Download/ubuntu19.tar.gz && cd ~ && tar xf ubuntu19.tar.gz && rm -rf ubuntu19.tar.gz


Kali: cp /sdcard/Download/kali.tar.gz && cd ~ && tar xf kali.tar.gz && rm -rf kali.tar.gz


Debian: cp /sdcard/Download/debian.tar.gz && cd ~ && tar xf debian.tar.gz && rm -rf debian.tar.gz


Arch: SORRY BUT ARCH LINUX IS NOT AVAILABLE FOR OFFLINE DOWNLOAD DUE TO ITS FREQUENT MIRROR CHANGES


Manjaro: SORRY BUT ARCH LINUX IS NOT AVAILABLE FOR OFFLINE DOWNLOAD DUE TO ITS FREQUENT MIRROR CHANGES


Fedora: cp /sdcard/Download/fedora.tar.gz && cd ~ && tar xf fedora.tar.gz && rm -rf fedora.tar.gz


Void: cp /sdcard/Download/void.tar.gz && cd ~ && tar xf void.tar.gz && rm -rf void.tar.gz


Alpine: cp /sdcard/Download/alpine.tar.gz && cd ~ && tar xf alpine.tar.gz && rm -rf alpine.tar.gz
```

* Once the process is complete you are good to start the Ubuntu.
* Type `./start-<distroname>.sh` to start the Linux.  

