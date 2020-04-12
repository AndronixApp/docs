# Internal Storage 📂

![](../.gitbook/assets/sd_banner%20%281%29.png)

To mount internal storage you just need to run two commands.

First open new Termux session \(Swipe from left corner to right\) and type:

```text
termux-setup-storage
```

Now it will ask you for Storage permission. **Allow** the Storage permission.

Once you are done with it type:

```text
nano start-{distroname}.sh
```

Make sure to replace **{distroname}** with your specific distro name. 

Now search for line:

```text
#command+=" -b /sdcard"
```

If you find this line then remove it and change it to

```text
command+=" -b /sdcard"
```

If you don't find the line then add the above mentioned line as shown in the screenshot.

