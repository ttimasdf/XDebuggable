# XDebuggable

The Xposed module. Make your app `debuggable=true` on the fly.

Tested on Nougat 7.1.2, may work with any Android 6.0+ & Xposed.



This module hook the app picker for debug in `Developer Settings`  to make any app appears even without `debuggable=true` in their manifest and ROM marked as release (or any kind of _stock rom_). Meanwhile, It hooked Zygote to start the app (selected above) process with certain debug flag so that only **selected** app will start with debug server. This avoid the may-have overhead(opposite to XInstaller).

This module have NO user interface. Just install and activate in Xposed Installer then it worked. You can found a prebuilt version at [releases](/ttimasdf/XDebuggable/releases) page.

