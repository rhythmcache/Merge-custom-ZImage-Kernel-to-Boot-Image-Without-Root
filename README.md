# Merge-custom-ZImage-Kernel-to-Boot-Image-Without-Root
## Usage
This Script will only Work On Termux.
video tutorial - https://youtu.be/uFfbJuQ5G-A

## Installation
Rename Your original boot file to boot.img and rename Custom Kernel/Zimage file to Image and put it in your internal storage (/sdcard)...
then just run this command in Termux. 
```
pkg install git -y
git clone https://github.com/rhythmcache/Merge-custom-ZImage-Kernel-to-Boot-Image-Without-Root
cd Merge-custom-ZImage-Kernel-to-Boot-Image-Without-Root
chmod 777 ./*
./start
cd ~
rm -rf Merge-custom-ZImage-Kernel-to-Boot-Image-Without-Root
```
