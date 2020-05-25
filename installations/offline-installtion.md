---
description: "We know that sometimes Internet can be a real pain, but worry not! \U0001F605"
---

# Offline Installation

![](../.gitbook/assets/offline_banner.png)

## Instructions

{% hint style="warning" %}
Offline Installation is only available for Andronix Premium users.
{% endhint %}

Choose any distro and click on **Download Offline** to download the distro.

Once the distro is downloaded open Termux and follow the given commands:

* Type `termux-setup-storage` and enable Storage permission to Termux

```text
termux-setup-storage
```

* Below is the list of each Offline distro. Choose and run the command according to your downloaded distro

### Ubuntu 19

```text
cp /sdcard/Download/ubuntu19.tar.gz . && tar xf ubuntu19.tar.gz && rm -rf ubuntu19.tar.gz
```

### Ubuntu 18

```text
cp /sdcard/Download/ubuntu.tar.gz . && tar xf ubuntu.tar.gz && rm -rf ubuntu.tar.gz
```

### Kali Security OS

```text
cp /sdcard/Download/kali.tar.gz . && tar xf kali.tar.gz && rm -rf kali.tar.gz
```

### Debian

```text
cp /sdcard/Download/debian.tar.gz . && tar xf debian.tar.gz && rm -rf debian.tar.gz
```

### Fedora

```text
cp /sdcard/Download/fedora.tar.gz . && tar xf fedora.tar.gz && rm -rf fedora.tar.gz
```

### Ubuntu 19

```text
cp /sdcard/Download/void.tar.gz . && tar xf void.tar.gz && rm -rf void.tar.gz
```

### Alpine

```text
cp /sdcard/Download/alpine.tar.gz . && tar xf alpine.tar.gz && rm -rf alpine.tar.gz
```

### Void

```text
cp /sdcard/Download/void.tar.gz . && tar xf void.tar.gz && rm -rf void.tar.gz
```

* Once the process is complete you are good to start the Linux system.
* Type `./start-<distroname>.sh` to start the Linux.  

