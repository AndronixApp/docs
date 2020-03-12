---
description: This tutorial will guide you through the installation of Ubuntu 18 & 19.
---

# Ubuntu

![](../../.gitbook/assets/ubuntu_banner.png)

## Essential Information

Ubuntu provided by Andronix is open source including all the scripts needed for installing it. You can take a look at it [here](https://github.com/AndronixApp/AndronixOrigin).

**Download size** - 45 MB

{% hint style="warning" %}
The size mentioned above is not the size after installing Ubuntu but it's just the tar size that Andronix downloads. **This doesn't include a desktop environment for the GUI**.
{% endhint %}

## How to Install?

### Ubuntu 18

* Open the[ Andronix App](https://andronix.app/) and click on the Ubuntu card.
* Select the version you want to install, namely 18.04

![](../../.gitbook/assets/ubuntu_selection.png)

* Click the **Install** button.

![](../../.gitbook/assets/ubuntu.png)

* Tap "**Copy**" button and then tap "**Termux**" to go the Termux app.
* Use the command below to update your termux packages so that you're running the updated versions of the required packages.

```text
pkg update
```

![](../../.gitbook/assets/termux-1.png)

* Tap & hold anywhere on the screen and press **Paste**.
* Press **Enter** and wait till the installation completes. 
* Type the following command to start the distro ****and press enter.

```text
./start-ubuntu.sh
```

* Now if you see `root@localhost` in Termux then you have successfully started Ubuntu

{% hint style="danger" %}
This only includes the bare-bone Ubuntu system that can be used through a CLI \(Command Line Interface\). To install a **desktop environment** follow the guide here.
{% endhint %}



### Ubuntu 19

* Open the[ Andronix App](https://andronix.app/) and click on the Ubuntu card.
* Select the version you want to install, namely 19.04. More info on that [here](https://itsfoss.com/ubuntu-19-04-release-features/).

![](../../.gitbook/assets/ubuntu_selection.png)

* Click the **Install** button.

![](../../.gitbook/assets/ubuntu.png)

* Tap "**Copy**" button and then tap "**Termux**" to go the Termux app.
* Use the command below to update your termux packages so that you're running the updated versions of the required packages.

```text
pkg update
```

![](../../.gitbook/assets/termux-1.png)

* Tap & hold anywhere on the screen and press **Paste**.
* Press **Enter** and wait till the installation completes. 
* Type the following command to start the distro ****and press enter.

```text
./start-ubuntu19.sh
```

* Now if you see `root@localhost` in Termux then you have successfully started Ubuntu

{% hint style="danger" %}
This only includes the bare-bone Ubuntu system that can be used through a CLI \(Command Line Interface\). To install a **desktop environment** follow the guide here.
{% endhint %}

