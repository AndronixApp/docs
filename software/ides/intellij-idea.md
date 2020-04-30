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
* We can now proceed to run Idea, navigate to **Desktop/ideaIU-2xxx.x.x/bin** and execute the `idea.sh` with the following command

```text
./idea.sh
```

* Yay! 🎊 That's all you need to do to run IntelliJ on your device. 

