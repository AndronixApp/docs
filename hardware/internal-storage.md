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

If you don't find the line then add the above mentioned line as shown in the screenshot below.

![](../.gitbook/assets/strorage_ss.png)

{% file src="../.gitbook/assets/start-debian.sh" caption="Here\'s an example of the file 🗃" %}

Once you are done with it press **Ctrl+X** and then press **Y** and then enter. Now start your linux system and do `cd /` . Now you will be able to see a folder **sdcard** which means you have successfully mounted your Internal Storage.

