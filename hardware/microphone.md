# Microphone 🎙

Andronix support mic input as well but only inside the **Modded OS**. You may use it to work on an audio editing or manipulation software like **Audacity, Mixxx, Cecilia**. 

{% hint style="danger" %}
This will not work on normal OS for now. We are working to support them soon.
{% endhint %}

{% hint style="danger" %}
Enabling both the speaker output and mic input will make a loop of your voice. The speaker will output something, the mic will receipt  it and will cause **echos**. The best thing you can do is to disable audio output when you need to use the microphone.
{% endhint %}

Follow these steps to set everything up -

* Fire up your Linux distro and paste this command **inside the Linux** \(not in Termux\)

```bash
sudo apt install wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Rootfs/Ubuntu19/micsetup.sh && chmod +x micsetup.sh && ./micsetup.sh && rm -rf micsetup.sh
```

Viola! 😎 You just got the microphone support.

