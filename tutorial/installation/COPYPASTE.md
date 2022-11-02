# Prerequisites

This is for people that just want to copy and paste evry command quickly. I recommend following the [normal guide](https://github.com/afastaudir8/sunst0rm-guide-linux/blob/main/tutorial/installation/PREREQUISITES.md). 

## Before anything

Type `su` into the terminal. This will automatically run every command as root without the need for `sudo` **This guide assumes that you're doing this.**

## Git

[Download it here](https://git-scm.com/download/linux)

## libimobiledevice

Since setting up libimobiledevice deppends on your distro, you have to find how to set it up for your distro. [Here's a good place to start.](https://github.com/afastaudir8/sunst0rm-guide-linux/blob/2.0/tutorial/installation/PREREQUISITES.md#libimobiledevice)

## futurerestore

Grab the [latest action](https://github.com/futurerestore/futurerestore/actions/workflows/ci.yml) and paste it [here](https://nightly.link/). Grab the `RELEASE` build for Linux.

Once it's downloaded, extract the zip and tarball then run 

```
mv ./futurerestore /usr/local/bin
chmod +x /usr/local/bin/futurerestore
futurerestore
```

Once it's done moving, you should get an output that looks like this:

![image](https://user-images.githubusercontent.com/45905959/199387103-c7fe55d6-0861-4646-863a-b4d87425baca.png)


## iBoot64Patcher

