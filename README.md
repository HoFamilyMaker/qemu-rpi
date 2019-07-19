# qemu-rpi
This repo contains QEMU start.bat file and kernel which allow to emulate Raspberry Pi 3 on you machine.

### Run on Windows&trade;
- Download and unpack latest version of QEMU from https://www.qemu.org/download/
- Download from https://downloads.raspberrypi.org/raspbian_lite/images/raspbian_lite-2018-11-15/2018-11-13-raspbian-stretch-lite.zip and unpack Raspbian image to folder with QEMU
- Clone this repo to somwhere and copy all file to QEMU folder
- Run **start.bat** and wait until machine starts 
- Try to connect it via SSH with login **pi** and password **raspbian**
`PS C:\> ssh pi@127.0.0.1 -p 5555`
