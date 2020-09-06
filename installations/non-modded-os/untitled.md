---
description: This tutorial will guide you through the installation of Debian.
---

# Debian

![](../../.gitbook/assets/deb_banner.png)

## Essential Information

Debian provided by Andronix is open source including all the scripts needed for installing it. You can take a look at it [here](https://github.com/AndronixApp/AndronixOrigin).

**Download size** - 75 MB

{% hint style="warning" %}
The size mentioned above is not the size after installing Debian but it's just the tar size that Andronix downloads. **This doesn't include a desktop environment for the GUI**.
{% endhint %}

## How to Install?

* Open the[ Andronix App](https://andronix.app/) and click on the Debian card.
* Click the **Install** button.

![](../../.gitbook/assets/deb.png)

* The first three options will install Debian with the mentioned [Desktop Environment](https://en.wikipedia.org/wiki/Desktop_environment). The last **Non-DE** variant installs Debian without any Desktop Environment and is recommended for using the distro only with a _Command Line Interface_.

{% hint style="success" %}
We recommend to choose **XFCE variant** as it is the most stable, smooth, advanced and customizable Desktop Environment present at the moment
{% endhint %}

![](../../.gitbook/assets/debian_install_sheet.png)

* Use the command below to update your termux packages so that you're running the updated versions of the required packages.

```text
pkg update
```

![](../../.gitbook/assets/termux-1.png)

* Tap & hold anywhere on the screen and press **Paste**.
* Press **Enter** and wait till the installation completes. 
* Type the following command to start the distro ****and press enter.

```text
./start-debian.sh
```

* Now if you see `root@localhost` in Termux then you have successfully started Debian.

### Exiting VNC

Exiting and stopping the VNC server gracefully is important to avoid any ghost process to be running and rendering the server almost useless. Read about how to exit the VNC server in this article.

{% page-ref page="../../vnc/vnc-basics.md" %}



