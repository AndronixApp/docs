# VNC Basics

## How to start VNC Server

First of all you need to make sure that you have any Desktop Environment installed in your LInux OS. If you are sure about then do:

```text
vncserver-start
```

Now just downlaod any VNC Viewer app from play store and connect to `localhost:1`

## How to stop VNC Server

It is very necessary to stop VNC server once you are done with it. To stop the VNC Server type:

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

## How to access VNC Server on other device

You can access VNC over PC or any other device but for that your both devices need to be in the same network i.e. both the devices should be connected to the same WiFi. If you dont have access to wifi you can start the hotspot from the device having the Linux installed and connect the other device to the hotspot. Once your both the devices are under same network do:

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

and copy then **wlan** IP address \(eg. 192.168.xx.xx\). Now use this IP Address on the other device with the port number as 1 \(eg. 192.168.xx.xx:1\).  

