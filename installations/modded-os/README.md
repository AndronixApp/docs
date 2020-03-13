---
description: >-
  Modded OS are version of normal distros optimized, beautified and made super
  stable by our experienced developers. These include Ubuntu, Debian, Manjaro
  for now. We carefully choose what goes into the
---

# Modded OS

![](../../.gitbook/assets/moddedos_banner.png)

## What are Modded OS?

Modded OS are modified by us to achieve the maximum performance and we ship it with all the essential software pre-installed. Themes and icons are selected to match every element of the system. 

## When should I choose Modded OS?

Well, every time to don't want to keep yourself busy with optimizing things and fixing those theming issues, finding the correct PPA for the installation of the working version of the software. All-in-all, it allows you to enjoy Linux without making you do everything necessary.

## How do they look like?

You can take a look at our [Modded OS Gallery](https://andronix.app/modded-os-gallery/).

## How do I install these OS?

* You need to login into Andronix either with your Google account or email \(register if you already have an account\). Worried about your privacy? Read more [here](../../security/data-protection.md).
* After logging in, click on the Install button of your favourite distro.

{% hint style="info" %}
**Confused** about which distribution to choose? here is a guide to help you out - _Modded OS Guide_
{% endhint %}

* If you haven't already purchased the distro, the app will prompt you to buy it first. You can proceed to the next step, if you already own the distro you want to install, else you can proceed to buy it.

{% hint style="info" %}
Modded OS are a **life-time purchase** and can be used on any number of devices.
{% endhint %}

_If already bought, the app will generate a one-time code for you to download the OS._

* That's it, let's proceed to the actual installation now. Click on the **Copy** button and paste the copied code in a **Termux shell**.
* Let it finish. The installation will take some time as these are much bigger than the normal \(un-modded OS\) because these have things pre-installed.
* When the download and extraction will finish, your termux will look something like this-



* You now need to start the distro with the following command

```text
./start-andronixos.sh
```

* This will start the post-installation process i.e. setting up the essential packages. You will need to wait until this finishes.
* If the post-installation setup successfully executed, you will see a **blue screen** asking for a _username._ You can choose any username unless that's a reserved keyword like _admin, root etc._ \(your name works fine\). Press **Enter** to proceed.

{% hint style="info" %}
If you can't access your keyboard for entering the username, press the **ESC** key at the bottom. This restarts the script and this time make sure that you have your keyboard out \(click anywhere on the terminal\) when you're in the Termux shell.
{% endhint %}

* The second thing the script asks for is your name. This can be anything to like. Again press **Enter** to proceed.
* Next you need a **Password**. You can choose any password as long as it is longer than 6 characters. Press **Enter** to proceed. Confirm the password by re-entering it and press enter to continue.
* Now you need a **Root Password.** You can choose any password as long as it is longer than 6 characters. Press **Enter** to proceed. Confirm the root password by re-entering it and press enter to continue.
* The next screen will show all the information entered. Check if those are the correct passwords and username \(if not, press _esc or back button_ to restart the script\). Press **Enter** to proceed.
* Now, wait until the system is creating the user. You should see something like this while the system is setting-up the user.

 

