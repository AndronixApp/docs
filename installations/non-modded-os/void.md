---
description: This tutorial will guide you through the installation of Void.
---

# Void

## Essential Information

Void provided by Andronix is open source including all the scripts needed for installing it. You can take a look at it [here](https://github.com/AndronixApp/AndronixOrigin).

**Download size** - 75 MB

{% hint style="warning" %}
The size mentioned above is not the size after installing Void but it's just the tar size that Andronix downloads. **This doesn't include a desktop environment for the GUI**.
{% endhint %}

## How to Install?

* Open the[ Andronix App](https://andronix.app/) and click on the Void card.
* Click the **Install** button.

![](../../.gitbook/assets/void.png)

* The first three options will install Void with the mentioned [Desktop Environment](https://en.wikipedia.org/wiki/Desktop_environment). The **Non-DE** variant installs Void without any Desktop Environment and is recommended for using the distro only with a _Command Line Interface_. The last three options will install Void with the mentioned [Windows Manager](https://en.m.wikipedia.org/wiki/Window_manager).

{% hint style="success" %}
We recommend to choose **XFCE variant** as it is the most stable, smooth, advanced and customizable Desktop Environment present at the moment
{% endhint %}

![](../../.gitbook/assets/void_install_sheet.png)

* Use the command below to update your termux packages so that you're running the updated versions of the required packages.

```text
pkg update
```

![](../../.gitbook/assets/termux-1.png)

* Tap & hold anywhere on the screen and press **Paste**.
* Press **Enter** and wait till the installation completes. 
* Type the following command to start the distro _\*\*_and press enter.

```text
./start-void.sh
```

* Now if you see `root@localhost` in Termux then you have successfully started Void.

### Exiting VNC

Exiting and stopping the VNC server gracefully is important to avoid any ghost process to be running and rendering the server almost useless. Read about how to exit the VNC server in this article.

{% page-ref page="../../vnc/vnc-basics.md" %}

