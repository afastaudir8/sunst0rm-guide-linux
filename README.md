# sunst0rm-guide-linux
This is a guide on how to use sunst0rm natively on Linux 

There are two ways to use sunst0rm on Linux. The first is using a [KVM](https://github.com/Arna13/sunst0rm-guide/blob/main/docs/misc/LINUX.md) which is what I'd personally recommend doing.

But let's say that a KVM doesn't work for you or you just want to use it natively on Linux. In that case, you can use [MCApollo's fork](https://github.com/MCApollo/sunst0rm) which is what this guide will focus on.


## Issues disabled

Please ask for help in [miniexploit's Discord server](https://discord.gg/h6eqnzue9P). I don't have the time to help fix issues with a script that has been dead for months now. sorry.

## Notes
This guide may be a bit confusing. If it doesn't work well for you, use [Arna13's guide using a KVM.](https://github.com/Arna13/sunst0rm-guide/blob/main/docs/misc/LINUX.md)

This **ONLY** works on checkm8 devices (A11 and lower)

A10 devices and up will lose some features (Audio output, vibration, and home button)

While extremely rare, please note that this script can **irreversibly brick your device. Mineek, arna13, afastaudir8, etc. are not responsible for ANY damage done to your devices. You have been warned** 

The iPhone X will have no touch recognition. The iPhone 8 and 8 Plus will work fine but with the aforementioned limitations.

**DO NOT** do this on your main device. This should only be done on a secondary device.

This guide has only been done on Ubuntu 22.04. Other distros *should* work too, however.

Some help is needed with parts of the guide as I haven't done this on other distros

If you need support with sunst0rm, don't be afraid to ask in the [official Discord server](https://discord.gg/h6eqnzue9P)

# Table of contents

- Getting sunst0rm working
 
  - [Dependencies](tutorial/installation/PREREQUISITES.md): This will show you how to get the basic dependencies working
  - [Restoring](tutorial/installation/RESTORE.md) This will show you how to restore your device
  - [Booting](tutorial/installation/BOOT.md)
 
  
  

    
  
 >  **Warning**
 > I am **not** responsible for any damage you may cause to your device or data. Make sure to backup the data on your iDevice before proceeding with this guide.
 
### This guide is heavily inspired from [Arna13's sunst0rm guide for macOS.](https://github.com/Arna13/sunst0rm-guide)
