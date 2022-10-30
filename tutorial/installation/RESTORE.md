# Restoring your device

> **Warning**
> This part of the guide will nuke all the data on your device. Make sure to back it up.

## Command
To restore, you'll need to add a few arguments to your command

The command will look like this:
```
./sunstorm.py -i 'IPSW' -t 'SHSH2' -d 'BOARDCONFIG'
```
- Required:
  - `IPSW` Is the path to the IPSW of the iOS version you want to downgrade to

  - `SHSH2` Is the path to the SHSH2 blobs you're going to use. The blobs can be for **any** iOS version for your device. They just need to be for **your** device and they need to be valid blobs

  - `BOARDCONFIG` Is, obviously, the board config for you device. For example: an iPhone 7 Plus (GSM) will be `D11AP` (or `D111AP`)

 - Required depending on device
    - `-kpp` **REQUIRED** for devices that have between an A7 and A9X chip. **Don't use this argument on anything above the A10.** 

## To restore, you need to be in pwnDFU mode. 
To enter pwnDFU, I recommend using gaster.
Run
```
git clone --recursive https://github.com/0x7ff/gaster
cd ./gaster
make libusb
```
Once it's done, when your device is in pwnDFU, run `./gaster pwn`.

Now you should be able to restore.

### AMD CPUs can have issues with entering pwnDFU mode


