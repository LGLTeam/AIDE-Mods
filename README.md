# AIDE Mods
AIDE is an integrated development environment (IDE) for real Android Applications directly on Android devices. These mods works better than the original AIDE.

# Download
APK Mods
* [AIDE CMODs 3.2.200108 (Editt-CMODs/CoRinga Modz)](https://secufiles.com/nE9J/AIDE_CMODs_3.2.200108.apk) (Recommended version)
* [AIDE Lite Mod 3.2.190514 (timscriptov)](https://mega.nz/file/bIpCQL6I#BzyLf1pB1Sf7EayW_PEJHl3f50qHHZDdb0BpB8FYdVo)

NDK
* [ndk_arm.tar.gz](https://mega.nz/folder/2c1TWIJD#UCzO7kIo1e4WpFwZHIMYVw/file/XRlRTIjJ) - NDK for 32-bit/ARMv7 phones
* [ndk_arm64.tar.gz](https://mega.nz/folder/2c1TWIJD#UCzO7kIo1e4WpFwZHIMYVw/file/7RdTzYxQ) - NDK for 64-bit/ARM64 phones

# Setting up AIDE

Now let's begin

Firstly, make sure you know your phone's hardware, and download correct NDK file coresponding to your phone's CPU architecture. ndk_arm.tar.gz for 32-bit/ARMv7 phones, ndk_arm64.tar.gz for 64-bit/ARM64 phones. Installing incorrect version will cause problems

Now install NDK support for modded AIDE. Click on 3 dots on the right-corner. Click **More... - Settings**

![](https://i.imgur.com/LyZMkK1.png)

Go to **Build & Run**, and click on **Manage native code support**.

![](https://images2.imgbox.com/6e/5c/DootVB4P_o.png)

A prompt will ask to input the path of NDK file.

If you use X-plore, you can show details of the file and copy file path easly.

![](https://images2.imgbox.com/54/2b/G0gVbhrN_o.png)

Paste it in the prompt box.

![](https://images2.imgbox.com/e1/c0/HSj9yQS9_o.png)

Click install and wait

![](https://images2.imgbox.com/1d/55/7LPXB7CI_o.png)

After installiation, you can now use AIDE with NDK support

# Opening project in AIDE

On the main screen, it says **No open files**. We simply click on **No open files** to show file explorer. Navigate to the directory of the project and open **app** folder

An option **Open Android app Project** will appear. Click on it to open

![](https://images2.imgbox.com/dc/7f/Jtq8ZEl1_o.png)

Now that the file explorer will look like this, means the project has been opened

![](https://images2.imgbox.com/2f/9a/EA0zZr8R_o.png)

# Run the app

Press play to compile the project

If successful, it will ask you to install the APK. It may ask you to allow installation from unknown sources. Please allow when asked

Run the app

# AIDE Troubleshooting

Problem with the project like app crashes: click **More... -> Project -> Refresh Build**. This will clear the project cache and fix problems

Problem with AIDE: Open System Settings -> Apps and clear data of AIDE app. This will reset everything and you need to install NDK again

AIDE has a lot of compatibility issues, you need to research a lot and do some trial and errors until you fix something.
