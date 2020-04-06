# BL1Plugins

In this repository you can find my Borderlands 1 Plugin(s).

So far there is only ONE. And that is a SanityCheck Bypass, which also is only for the non-"Enhanced" version of BL1.

# Installation
First, download the archive from [here](https://github.com/c0dycode/BL1Plugins/raw/master/BL1%20SanityCheck%20Bypass.zip).

If you're familiar with my other [PluginLoader](https://github.com/c0dycode/DLLPluginLoader), it works exactly the same.

In this case, the PluginLoader requires two files.
Make sure **libresample.dll** and **libresample_org.dll** are in the Binaries-folder. This is right next to the **Borderlands.exe**. Do NOT rename either of them.

After that, make sure the **Plugins** folder is also in the **Binaries**-folder.

TLDR: Drag & Drop the files from the archive next to your **Borderlands.exe**.
If you're being asked about overwriting "libresample.dll" then confirm.

# Issues?
If it doesn't work for you, make sure you have [this vcredist_x86](https://aka.ms/vs/16/release/vc_redist.x86.exe) installed. Yes x86 is correct, even if you are on a x64 system/OS.