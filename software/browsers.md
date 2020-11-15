---
description: "Where the web lives...\U0001F30D"
---

# Browsers

![](../.gitbook/assets/firefox_banner.png)

{% hint style="warning" %}
If you are having any **armv7 based device** browsers might fail to work due to unknow reasons. We can't help with armv7 devices since we don't have any armv7 devices as its older architecture and is no more found in modern smartphones.
{% endhint %}

{% hint style="danger" %}
## All the commands should be executed after starting Linux
{% endhint %}

## Firefox

### Ubuntu / Ubuntu 20 / Debian / Kali Linux

```text
apt install firefox-esr -y
```

### Arch / Manjaro

```text
pacman -S firefox --noconfirm
```

### Void Linux

```text
xbps-install -S firefox
```

### Alpine

{% hint style="danger" %}
Sadly Alpine does not provide Firefox support for ARM devices as or now.
{% endhint %}

![](../.gitbook/assets/chrome_banner.png)

## Chromium

### Ubuntu / Ubuntu 19 / Debian / Kali Linux

```text
wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Uninstall/ubchromiumfix.sh && bash ubchromiumfix.sh
```

If the Chromium does not launch from Application Menu then try the following command inside VNC terminal:  
1- `chromium --no-sandbox`

2- `chromium-browser --no-sandbox`

### Arch / Manjaro

```text
pacman -S chromium --noconfirm
```

### Void Linux

{% hint style="danger" %}
Sadly chromium is not available for Void Linux.
{% endhint %}

### Alpine

```text
apk add chromium
```

### Fedora

```text
dnf install chromium 
```

