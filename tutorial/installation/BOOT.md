### Booting

To boot the device, you must run the same command you did earlier but add `-b`  and `-id 'IDENTIFIER'`

`'IDENTIFIER'` Is your device's model identifier. For example, an iPhone 8 GSM model will be `iPhone10,4`

If you try booting the device normally, it should show a black screen. From here, get into DFU mode and run `./boot.sh`

Your device should now boot!

> **Note**
>When you do this for the first time, it will verbose boot and turn off. Repeat the steps above to boot it again.

Now, if your device boots to the "Hello" screen, congratulations! You have successfully tether downgraded your device!

From now on (until you restore) you have to repeat the steps under "Booting" to boot the device if the battery dies or if you reboot the device.
