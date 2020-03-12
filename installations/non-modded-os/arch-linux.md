# Arch Linux



## Essential Information

Arch Linux provided by Andronix is open source including all the scripts needed for installing it. You can take a look at it [here](https://github.com/AndronixApp/AndronixOrigin).

**Download size** - 45 MB

{% hint style="warning" %}
The size mentioned above is not the size after installing Arch Linux but it's just the tar size that Andronix downloads. **This doesn't include a desktop environment for the GUI**.
{% endhint %}

## How to Install?

Open the[ Andronix App](https://andronix.app/) and click on the Arch Linux card.

Select the version you want to install, namely 18.04 or 19.04. More info on that [here](https://itsfoss.com/ubuntu-19-04-release-features/).

Click the **Install** button.

Tap "**Copy**" button and then tap "**Termux**" to go the Termux app.

Use the command below to update your termux packages so that you're running the updated versions of the required packages.

```text
pkg update
```

Tap & hold anywhere on the screen and press **Paste**.

Press **Enter** and wait till the installation completes. 

Type the following command to start the distro ****and press enter.

```text
./start-arch.sh
```

Now if you see `root@localhost` in Termux then you have successfully started Arch Linux.

{% hint style="danger" %}
This only includes the bare-bone Arch Linux system that can be used through a CLI \(Command Line Interface\). To install a **desktop environment** follow the guide here.
{% endhint %}

