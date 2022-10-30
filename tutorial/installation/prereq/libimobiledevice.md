# Installing libimobiledevice
Installing libimobiledevice depends on your distro. 

For example, to do it on **Ubuntu**, you have to install the requirements like this:
```
sudo apt install build-essential pkg-config checkinstall autoconf automake libtool-bin libreadline-dev libusb-1.0-0-dev
```
Then run 
```
git clone https://github.com/libimobiledevice/libimobiledevice.git
cd libimobiledevice
```
And then 
```
./autogen.sh
make
sudo make install
```

As I said earlier, it depends on the distro so you have to find how to install it for your distro.
