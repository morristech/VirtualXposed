
[中文文档](CHINESE.md "中文")

Introduce
------------
**VirtualXposed** is a simple APP based on [VirtualApp](https://github.com/asLody/VirtualApp) and [epic](https://github.com/tiann/epic) to use Xposed Module without root, unlock the bootloader, or flash the system image.（Support Android 5.0~8.1)。

Warnning
-----------

No use for Commercial Purposes!!!  Please refer VirtualApp's [declaration](https://github.com/asLody/VirtualApp) 

Usage
-------

### Prepare

Download the latest apk in [Relase page](https://github.com/android-hacker/VirtualXposed/releases) , then install it on your Android phone.

### Install APP and Xposed module

Open VirtualXposed, Click the ➕ in home page, add the APP and Xposed module to VirtualXposed's virtual environment.

Notice: **All operation（install Xposed module, APP）must be done in VirtualXposed**, Otherwise, the Xposed module won't take effect!! For example, If you install Youtube APP on your system（Your phone's original system, not in VirtualXposed）,and then install Youtube AdAway(A Youtube Xposed module) in VirtualXposed; Or you install Youtube in VirtualXposed, and install Youtube AdAway on original system; or both of them are installed on original system, **These three case won't take effect!**。

![How to install](https://raw.githubusercontent.com/tiann/arts/master/vxp_install.gif)

There are three ways to install APP or Xposed module to VirtualXposed:

1. clone the original system's installed apps. Click ➕ in home page, the first page are installed apps.
2. install via apk file. (Click ➕ in home page, the second page are apks found in your sdcard)
3. install via external file chooser. (Click ➕ in home page, use the float button to choose apk file to install)

For Xposed module, You can install it from Xposed Installer, too.

### Active the Xposed module

Open Xposed Installer in VirtualXposed, go to the module fragment, check the module you want to use:

![How to active module](https://raw.githubusercontent.com/tiann/arts/master/vxp_active.gif)

### Reboot

Reboot the VirtualXposed, **No need to reboot your phone**; Just click Settings in home page of VirtualXposed, Click `Reboot` Button, VirtualXposed will reboot like a shot. 

![How to reboot](https://raw.githubusercontent.com/tiann/arts/master/vxp_reboot.gif)

Supported Modules
--------------------

- 微X模块
- 微信巫师
- 应用变量
- 音量增强器
- 微信学英语
- 冲顶助手
- 情迁抢包
- 微信跳一跳助手
- 步数修改器
- 模拟位置
- 指纹支付

Far more than above.

Known Issues
-------------

1. Can not modify system, so the Module used to modify system can never take effect.
2. Do not support Resource hooks now.
3. May be some modules are not compatible with VirtualXposed now.

Support
-----------

Welcome to contributing for VirtualXposed!!

For Developer
--------------

- [Fire a bug](https://github.com/android-hacker/exposed/issues)
- [Wiki](https://github.com/android-hacker/VirtualXposed/wiki)

Thanks
-------

1. [VirtualApp](https://github.com/asLody/VirtualApp)
2. [Xposed](https://github.com/rovo89/Xposed)