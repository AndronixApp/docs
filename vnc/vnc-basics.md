---
description: "Confused about VNC? We got you covered here. \U0001F60E"
---

# VNC Basics 📱

![](../.gitbook/assets/vnc_banner.png)

## How to start VNC Server

First of all you need to make sure that you have any Desktop Environment installed in your LInux OS. If you are sure about then do:

```text
vncserver-start
```

Now just download any VNC Viewer app from play store and connect to `localhost:1`

## How to stop VNC Server

**It is very necessary to stop VNC server once you are done with it or you are exiting the Linux distro**. To stop the VNC Server type:

```text
vncserver-stop
```

Once you do it, terminal will ask you for port number. Enter **1** as port number and click enter.

## How to change VNC Server resolution

To change the VNC Server resolution type:

```text
nano /usr/local/bin/vncserver-start
```

Now change the last line to:

```text
 vncserver -name remote-desktop -geometry 1920x1080 :1
```

You can change the resolution according to your device and then restart/start the VNC Server.

Once you are done just press `Ctrl+X` and then typen **Y**  and then hit enter.

## How to change picture quality in VNC

If you are using BVNC then you do not need to make any changes. It will make its required changes itself

If you are using RealVNC Viewer then connect to the VNC Server and then click on **i**  button at the top and then change _**Picture Quality**_  to _High_ or your desired quality.

## How to access VNC Server on other devices

You can access VNC over PC or any other device but for that your both devices need to be in the same network i.e. both the devices should be connected to the same Wi-Fi. If you don't have access to Wi-Fi you can start the hotspot from the device having the Linux installed and connect the other device to the hotspot. Once your both the devices are under same network do:

```text
nano /usr/local/bin/vncserver-start
```

Now edit the last line to:

```text
vncserver -name remote-desktop -geometry 1920x1080 -localhost no :1
```

If you are using any Linux OS which is Arch based distro then you need to change the to:

```text
vncserver -name remote-desktop -geometry 1920x1080 -localhost :1
```

Once you are done with this open a new Termux session and type:

```text
ip a
```

and copy then **WLAN** IP address \(eg. 192.168.xx.xx\). Now use this IP Address on the other device with the port number as 1 \(eg. 192.168.xx.xx:1\). 

### For people without access to another device to create a hotspot but still use vnc on other device

And now, Say you don't have access to another device or phone which you can use as a hotspot, Well there is a fairly easy soltion to that, All we need to do is port forward the ```localhost:rfb port``` to the internet and then later you can connect to it

Here is how you do it

First, create an account on [ngrok.com](https://ngrok.com) and on the getting started page you can see different options for download.

Copy the direct link to `Linux Arm` file and now open termux.

Type `wget <link here>` and it will download ngrok to your device.

Now, unzip it `unzip ngrok-stable-linux-arm.zip`

now move it /usr/bin ```mv ngrok /usr/bin```

After that, from ngrok's website you have your auth token along with the command written there, copy the whole command but remove `./` from it

After executing the command it should say something like ```Added auth token to.........```

Now start the vncserver using `vncserver-start` and type `vncserver -list`

You should see the RFB Port of you VNCServer, We will be port forwarding it so remember that

Port Forwarding using this command, ```ngrok tcp <port here>```
                                       in our case it is 5901
                                       so
                                    ```ngrok tcp 5901```
Now it should connect to ngrok servers and give you an address something like ```0.tcp.ngrok.ip:13002```

Note: The numbers will be different in your case

Now, goto your vnc viewer client on other device be it windows, android or any other

And simply input that ip address which has ngrok given you and connect to it and then input the password you had set earlier

**Troubleshooting:** **My ngrok is stuck on reconnecting/connecting or will not connect***
             Sol:  Well just turn on your mobile hotspot on the phone which you are trying to connect to ngrok with, be sure to close your linux distro before you turn on ngrok again with wifi hotspot on.





### How to change resolution permanantly in Modded OS / Ubuntu 19

To change resolution permanantly type:

```text
nano /usr/local/bin/vnc
```

Once you do this replace the second line with:

```text
LD_PRELOAD=/lib/aarch64-linux-gnu/libgcc_s.so.1 vncserver -localhost no -depth 24 -name remote-desktop -geometry 1920x1080 :$PORT
```

You can change the resolution according to your device and then restart/start the VNC Server.

Once you are done just press `Ctrl+X` and then typen **Y**  and then hit enter.

Now when you'll do just choose the first option i.e. _Start vncserver with autodetect/dynamic resolution_ 

