# ACNHMobileSpawner

Item injector for Animal Crossing: New Horizons for mobile built in Unity. Confirmed working on Windows, Mac, Linux, Android and iOS.
Requires a Switch running custom firmware with the sysmodule [sys-botbase](https://github.com/olliz0r/sys-botbase) or [USB-Botbase](https://github.com/fishguy6564/USB-Botbase) installed.

It currently supports the following:
* Injecting and deleting inventory items.
* Changing amount of miles, bells in your bank and in your wallet (inventory).
* [Changing and replacing villagers](https://www.youtube.com/watch?v=5CUUZhGtsxk) using the perfect villager database.
* Changing the turnip buy/sell prices and fluctuations.
* Loading item cheats (using the NHSE cheat parser).

Refer to the [Wiki](https://github.com/berichan/ACNHMobileSpawner/wiki) for help and troubleshooting.

Based heavily on [NHSE](https://github.com/kwsch/NHSE).

You run this at your own risk, I'm not responsible for anything.

### Android and iOS builds

The application requires an Android device running at minimum Android 4.4 (KitKat) with support for OpenGLES2.

Builds are not guaranteed to be stable. You may download the [apk or ipa files here](https://github.com/berichan/ACNHMobileSpawner/releases).

iOS builds are auto-built and untested, but I've been told they work. 

### Screenshots

<img src = "https://user-images.githubusercontent.com/66521620/84556327-bcb53000-ad19-11ea-96c6-12dc65441efd.png" width = "300">

### Video guide

<a href="https://youtu.be/c5HJgwqeb7w" target="_blank"><img src = "https://i.imgur.com/XJnWZk2.jpg" width = "300"></a>

Click the image above.

### Notes

Some code was deleted and had to be rebuilt using ILSpy. I've done my best to clean up the classes affected, but they will be uncommented, minus ILSpy warnings I've kept in just to know what was affected.
