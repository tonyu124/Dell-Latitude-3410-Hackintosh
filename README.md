# Dell-Latitude-3410-Hackintosh 
Hi Everyone this is my first PC/Laptop Hackintosh Build that I have used for 1 1/2 years

It has been my daily driver and has taught me alot so I wanted to share my efforts with you.  

Dortania opencore post/blog helped me alot awhile back so I give them the credit for info but I really built this from scratch every step of the way


This is a Opencore build 
* **MacOS Version** Catalina 10.15.7

# What's working?
* **SMBIOS**: MacBookPro16,2 (Coffee Lake 10th gen) I3 10110u 2.1ghz but system report says 2.6ghz
* **Audio**: AppleALC.kext alcid=15 NVRAM patch 
* **Graphics**: Integrated Intel UHD 620 stolemen/stoelmen patch 
* **Wifi**: Intel Dual Band Wi-Fi 6 AX201 Heliport itlwm.kext modification needed for your network
* **Bluetooth** Intel AX201 IntelBluetoothInjector/IntelBluetoothFirmware Kexts
* **Mapped Thunderbolt and USB ports**: seems to work at correct speeds cant say they are slow in anyway ?
* **CPU Power Management**: SSDT-AWAC.aml 
* **Brightness Slider** SMC KEXTS and SSDT-PNLF-CFL.aml
* **OpenCore Boot** Windows 10/upgraded to Windows 11 Has booted on Sata SSD and macos was installed on M.2 NVME 
* **Trackpad/Keyboard**: VoodooPS2Controller.kext
* **Ethernet** RealtekRTL8111.kext 

# What's not working?
* Sometimes Trackpad randomly stops working after a sleep wake but spamming spacebar will turn on screen but u will need a usb mouse to navigate or reboot :/ 

* Mic on jack or regular seemed to not work but maybe it was bad headphones but idk about onboard mic ?

* This is a non-touch model so doesnt have touch Kexts

* Sdcard slot doesnt work but i havent tried any kext so next update maybe i can fix it :)

* Screen alot of the time will go black/nobacklight at boot for like 5 mins but after that 5 mins or so it will light up and brightness slider/keys on keyboard will control brightnes. it looks like it just died or turned off but its really just dim for 5 mins. Sometimes it just works happily with no dim just a wierd flicker.
