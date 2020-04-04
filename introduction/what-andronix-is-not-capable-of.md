# What AndroNix is not capable of !

Many users out there are looking for a viable resource to use Linux system on thier Android devices without rooting thier devices. AndroNix is a viable option for these purposes but with some limitations. We make our best efforts to provide a full Linux PC experience to our users but some things are just out of our hand due to certain restrictions imposed by the Android layer, its SELinux policies and the process we use to run the Linux on the Android devices. 

On this page you can find the summary of what AndroNix is not capable of doing with the reasons. So here is the list:



* AndroNix is not capable of running **STEAM** or any PC games on any of its Linux systems. The main reason for this is because Steam is only made for Intel/AMD based CPU's and not mobile based CPU's i.e. aarch64, armv8, arm64, arm, armv7, arm32 etc.



* AndroNix is not capable of running any software except softwares complied for **arm64/armv8/aarch64** architecure if you are using any **Android device** based of **Android 7** or above and has **arm64/armv8/aarch64** chipset. You can check your device architecture by using [**CPUZ**](https://play.google.com/store/apps/details?id=com.cpuid.cpu_z). If you are using any device which has Android layer such as **Chromebook** then AndroNix will only be able to run software made for your architecture which may be **i386/i686/x86 or x86\_64.** 

\*\*\*\*

* AndroNix does not claim that it will run all the softwares even if the software complies to all the conditions mentioned in the above point. If the software is made in such a way that it requires the presence of Linux Kernel or any hardware suppot which is not present in the **Proot environment.** AndroNix uses Proot environment which has certain unbypassable limitations leading to unusable softwares.



*  AndroNix is not made for compiling large chunks of code such as building an Android app or any softwares or compiling kernels. Code compilations sometimes require specific hardware which is not present in Proot environment which may lead to errors while compiling code. Any such reports on any support channel will not be entertained.



* 
