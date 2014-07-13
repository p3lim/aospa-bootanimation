## AOSPA 3+ Bootanimation

I pulled this from the [original ROM](https://plus.google.com/+ParanoidAndroidCorner/posts/c2orL7JAZZp) and ported it to be used in the [AOSPA4](https://plus.google.com/+ParanoidAndroidCorner)/[CM11](http://www.cyanogenmod.org/) Theme Engine.

Here's how it should look like, I've only tested this on the Nexus 4:

![](https://cloud.githubusercontent.com/assets/26496/3266600/8a320e0c-f2b5-11e3-88ce-8967d593465c.gif)

## Installing

Install it from the apk over [adb](https://developer.android.com/tools/help/adb.html) or from the phone itself

Apply from the Theme Engine


## Building

Make sure you have the [Android SDK](https://developer.android.com/), the [Java JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html) and [Ant](http://ant.apache.org/) installed and configured

Run `android update project --target 19 --path .` to set target API and add missing build files

Run `ant debug` to build an unsigned debug version
