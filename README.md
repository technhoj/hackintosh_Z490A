# Hackintosh_Z490A

Hi Everyone,

I have successfully installed Mac Os Big Sur in my computer with i7-10700k and Asus Prime Z490-A. My Efi and all my configuration can be found above.

![MacOS BigSur](https://github.com/technhoj/hackintosh_Z490A/blob/main/Media/BigSur.jpeg)

![RAM](https://github.com/technhoj/hackintosh_Z490A/blob/main/Media/RAM.png)

![Airdrop](https://github.com/technhoj/hackintosh_Z490A/blob/main/Media/Airdrop.jpeg)

![Sidecar](https://github.com/technhoj/hackintosh_Z490A/blob/main/Media/SIdecar.jpeg)

### Note: Change below key in config.plist

SystemSerialNumber

MLB

SystemUUID

SystemProductName: iMac20,1

#### Running OS: Big Sur 11,4

#### Running Bootloader: OpenCore Pkg 0.7.1 

## Hardware
|||
|-|-|
|Motherboard|Asus Prime Z490-A (BIOS v2201)|
|CPU|Intel i7 10700k|
|GPU| Asus Dual RX580 8G|
|RAM|Corsair Vengean 3200Mhz 23GB(2x16)|
|Storage|WD Black SN750 1TB|
|BT/WiFi|Fenvi T919|
|Ethernet| Intel® I225-V 2.5Gb Ethernet (haven’t tested)|
|Audio| Realtek ALC S1220A |

## What works:
Almost all works

For Sidecar to work, enable iGPU Multi-Monitor in BIOS
Make the changes in BIOS, per yilmazca guide https://github.com/yilmazca/intel-i9-10900K-Asus-prime-Z490A-hackintosh

Use hackintool for USB Port Map

## Tools I used:
ProperTree https://github.com/corpnewt/ProperTree

GenSMBIOS https://github.com/corpnewt/GenSMBIOS

MountEFI https://github.com/corpnewt/MountEFI

Hackintool https://github.com/headkaze/Hackintool
