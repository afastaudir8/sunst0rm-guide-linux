# Getting started

Before using sunst0rm, you obviously need to install the dependencies first.

## Git
To install most, if not all, of the requirements, you'll need [git](https://git-scm.com/download/linux)

## libimobiledevice
Installing libimobiledevice on Linux is dependant on your distro. 

[The official website](libimobiledevice.org) lists how to do it on openSUSE, Ubuntu, and Debian. 

libimobiledevice is also on AUR for arch based systems.

## Futurerestore

### Note: Do not ask for futurerestore related support in FDR Bureau or really any other jailbreaking related server as the issues are 99.99% of the time related to sunst0rm.

To use sunst0rm, you need to have a nightly build of futurerestore installed.

To do this, you go [here](https://github.com/futurerestore/futurerestore/actions) and copy the link to the latest action.

Then, go to https://nightly.link/ and paste the prevviously copied artifact.

You should now see this.

![image](https://user-images.githubusercontent.com/45905959/198892424-22035da2-35c5-40bb-88ab-2681f95bd8ac.png)

Download and unzip the `RELEASE` build for Linux. 

Once you unzip it, you should see these files:

![image](https://user-images.githubusercontent.com/45905959/198892732-26af33cf-d34b-4227-aef4-e91870062eb5.png)

Next, run `mv ./futurerestore /usr/local/bin` 

>You may need to run that command with `sudo`

Then run `sudo chmod +x /usr/local/bin/futurerestore`

If it worked, you should be able to run futurerestore just by typing `futurerestore`. It should display this

![image](https://user-images.githubusercontent.com/45905959/198892940-baf9a217-1c89-4723-b03d-23f7a30d18a7.png)

## iBoot64Patcher

iBoot64Patcherhas to be downloaded similarly to how to download futurerestore

A precompiled build can be found [here](https://github.com/Cryptiiiic/iBoot64Patcher/actions)

Copy the link to the latest artifact and paste it into https://nightly.link/ and download the `RELEASE` build of iBoot64Patcher

Once it's unzipped, run `mv ./iBoot64Patcher /usr/local/bin`.

Then run `chmod +x /usr/local/bin/iBoot64Patcher`.

Now, try running it by typing `iBoot64Patcher` in the terminal. iT'S CASE SENSITIVE.
