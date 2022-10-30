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

iBoot64Patcher has to be downloaded similarly to futurerestore

A precompiled build can be found [here](https://github.com/Cryptiiiic/iBoot64Patcher/actions)

Copy the link to the latest artifact and paste it into https://nightly.link/ and download the `RELEASE` build of iBoot64Patcher

Once it's unzipped, run `mv ./iBoot64Patcher /usr/local/bin`.

Then run `chmod +x /usr/local/bin/iBoot64Patcher`.

Now, try running it by typing `iBoot64Patcher` in the terminal. iT'S CASE SENSITIVE.

## Kernel64Patcher
At this point, you have to download sunst0rm using `git clone --recursive https://github.com/MCApollo/sunst0rm` You need to do this now to patch Kernel64Patcher and asr64_patcher later

Next, download Kernel64Patcher by running 
```
git clone https://github.com/iSuns9/Kernel64Patcher
cd ./Kernel64Patcher
```

But don't compile it *just* yet. You have to patch it first! 

You just need to run `patch -p1 </path/to/sunst0rm/linuxpatches/Kernel64Patcher.patch`

Then compile Kernel64Patcher by running `gcc ./Kernel64Patcher.c -o Kernel64Patcher -Iinclude-linux/`

If it compiled correctly, run `./Kernel64Patcher`. It should display this 

![image](https://user-images.githubusercontent.com/45905959/198894457-70f9ab7b-c990-4f25-894e-a57a34ca9d29.png)

If it worked, you should be able to run `mv ./Kernel64Patcher /usr/local/bin`

And then `sudo chmod +x /usr/local/bin/Kernel64Patcher`

You should able to run it with just `Kernel64Patcher`

## img4tool 
### For img4tool, you'll need to have [libssl1.1](https://packages.ubuntu.com/focal/amd64/libssl1.1/download) installed.

For img4tool, just download [buildroot_ubuntu-latest](https://github.com/tihmstar/img4tool/releases/tag/197) and only extract `/usr/local/bin/img4tool`

Once it's extracted, run `./img4tool`. 

This should be the output:

![image](https://user-images.githubusercontent.com/45905959/198895446-74140d56-22ae-4154-90a3-07cfbabf5e73.png)

If your output, look like this: 

![image](https://user-images.githubusercontent.com/45905959/198895471-408dafa5-32ae-4ed9-b76f-f319361132cc.png)

You need to install libssl1.1

Like the other dependencies, you'll need to run `mv ./img4tool /usr/local/bin`

Then run `sudo chmod +x /usr/local/bin/img4tool`

You should now be able to run it by typing `img4tool`

## img4

Grab the img4 file I left on the top directory of the guide. Compiling img4 from the source may lead to some issues later down the line. 

Once it's downloaded, simply run `mv ./img4 /usr/local/bin`

Then `sudo chmod +x /usr/local/bin/img4`

Typing `img4` should give you an output that looks like this.

![image](https://user-images.githubusercontent.com/45905959/198896258-9a0c37b8-60c5-4fe6-89cf-c8b97594a0fb.png)

