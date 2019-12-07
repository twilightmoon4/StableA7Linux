# StableA7Linux for iOS10.3.3

I come here to release you my beta of the StableA7 port for Linux

Is downgrade for iOS10.3.3 in A7 idevices

##What do you need to install?

 - A Ubuntu / Debian based Linux distro more recent (I recommend Xubuntu 19.10 which I use) , installed, no Live CD

 - Patience (very important)

 - A brain (very rare)

 - Your idevice in DFU mode

 - *Open Software&Updates (or Software Sources depending on your Linux distro or even Additional Drivers) and enable all sources on the Other Software tab

##Running the tool

```
git clone https://github.com/twilightmoon4/StableA7Linux.git
cd StableA7Linux
sudo apt-get update
chmod +x *
```
Place IPSW in same folder as script, renaming it `restore.ipsw`
```
sudo bash StableA7.sh
```
*(Warning, the exploit can be very inconsistent, so be patient)

Okay, after a long time before the exploit works, and congratulations ! your idevice will be on iOS 10.3.3 <3

Thanks to: 
  - @LinusHenze 
  - @mosk_i @tihmstar 
  - @a_i_da_n  
  - @ConsoleLogLuke
