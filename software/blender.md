# BLENDER

{% hint style="danger" %}
Blender will only work for very basic animation. Please use this keeping in your mind that you're using an Android device.
{% endhint %}

You can install GIMP to fulfil all your image editing needs as follows-

### APT

* Just paste this after starting the distro

```text
sudo add-apt-repository ppa:thomas-schiex/blender
sudo apt-get update
sudo apt-get install blender
```

### PACMAN

* Just paste this after starting the distro

```text
https://aur.archlinux.org/blender-2.8-git.git
cd blender-2.8-git
makepkg -si
```

If you don't want to build form the AUR, you can use [this ](https://gist.github.com/imprakharshukla/280de1a64c527775025836c15620e6cb)method instead.

### YUM \| DNF

* Just paste this after starting the distro

```text
sudo dnf update
sudo dnf install blender -y
```

