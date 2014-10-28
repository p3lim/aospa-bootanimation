## AOSPA 3+ Boot Animation

This is a modified version of the original boot animation for the Paranoid Android (AOSPA) 3+ project, repurposed to work with the CyanogenMod 11 Theme Engine.

It will work on most ROMs that feature the Theme Engine, although it has only been tested on AOSPA 4+.

Here is a preview of what it looks like:

![](https://cloud.githubusercontent.com/assets/26496/3266600/8a320e0c-f2b5-11e3-88ce-8967d593465c.gif)

### Installing

You can install this from the Google Play store, or by building it yourself and installing the package file.

Once installed, apply the boot animation from the Theme Engine.

### Building

Make sure you have the [Android SDK](https://developer.android.com/), the [Java JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html) and [Ant](http://ant.apache.org/) installed and configured

Run `android update project --target 19 --path .` to set target API and add missing build files

Run `ant debug` to build an unsigned debug version

### Legal

Non-profit, non-transferrable redistribution and branding rights for this theme, specifically the animation and the name, was granted by [+ValterStrods](https://plus.google.com/+ValterStrods) on behalf of the Paranoid Android Project (PA).

This project is in no way endorsed by PA, and PA reserves all rights of the original content.
