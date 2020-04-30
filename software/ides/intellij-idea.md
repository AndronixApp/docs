---
description: "This does everything! \U0001F605❤"
---

# IntelliJ Idea

![](../../.gitbook/assets/intellij_banner.png)

## Installation

Here are the steps needed to install IntelliJ Idea on your Andronix instance

{% hint style="warning" %}
This assumes that you have the **SDK for your language already installed** for the distro you are using.
{% endhint %}

### APT

* Download the latest tar.gz file from JetBrains official [download page](https://www.jetbrains.com/idea/download/#section=linux). 
* After downloading the tar.gz, make sure that it is in your download folder and after run the following command. **Change** **`x` to the name of the tar downloaded.**

```text
tar -xzf ideaIU-2xxx.x.x.tar.gz -C ~/Desktop/
```

* The tar should now be unzipped in `Desktop/ideaIU-2xxx.x.x`, where 'x' stands for the year and version number.
* Now choose the command from below and run it inside Linux terminal

For Debian/Ubuntu/Kali:

```text
sudo apt install openjdk-11-jdk -y
```

For Arch/Manjaro

```text
sudo pacman -S jdk-openjdk
```

For Void Linux:

```text
xbps-install -S openjdk
```

For Alpine:

```text
apk --no-cache add openjdk11 --repository=http://dl-cdn.alpinelinux.org/alpine/edge/community
```

For Fedora:

**Fedora is not recommended for use of Jetbrains IDE**

* We can now proceed to run Idea, navigate to **Desktop/ideaIU-2xxx.x.x/bin** and execute the `idea.sh` with the following command

```text
./idea.sh
```

* Yay! 🎊 That's all you need to do to run IntelliJ on your device. 

