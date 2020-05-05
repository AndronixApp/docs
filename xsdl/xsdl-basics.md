---
description: XSDL seems confusing?? Its really not
---

# XSDL Basics

It is X Window System / X11 server for Android. X11 servers are generally more faster when compared to VNC but XSDL lacks the beautiful UI which VNC Viewer has. It comes to your choice and what suits you the most amongst VNC and XSDL.

### How to start XSDL

* Download and install XSDL app from Play Store
* Open XSDL and wait until you see something similar to the screenshot below
* Now start OS and type the command inside Linux :

```text
export DISPLAY=127.0.0.1:0 && bash ~/.vnc/xstartup &
```

If you are of wifi network and want to access XSDL from another Android device then change the command to :

```text
export DISPLAY=192.168.0.100:0 && bash ~/.vnc/xstartup &
```

{% hint style="info" %}
Make sure to change the DISPLAY IP to your IP shown in the XSDL app. The IP Address should start with **192.168.x.x** 
{% endhint %}

