# Gigabyte B560M Aorus Elite + i5 10600KF + RX 5700 XT + Fenvi BCM94360CD

 ![Screenshot 2023-03-24 at 20 10 44](https://user-images.githubusercontent.com/44346970/227660107-6bf07ca0-9b7a-4016-967d-b3c246090765.png)

**Dual Boot**: Windows 11 + MacOs Ventura
<br>
**Latest working macOS**: 13.2
<br>
**Current OpenCore**: 0.9.0
<br>
**SMBios**: MacPro7,1

## Complete hardware specs
- Intel i5 10600K @ Stock (All cores (P+E+HT) activated)
- Gigabyte B560M Aorus Elite @ BIOS F8a
- RX 5700 XT - 8GB (Mllse - Aliexpress)
- 2x 8Gb DDR4 3200Mhz Gloway with XMP Enabled
- Wifi/BT Fenvi BCM94360CD - Work OOB

## What works
- Audio
- HDMI/DP
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything including GPU
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time
- Sleep
- Airdrop

## Kexts used:
- AppleALC.kext
- Lilu.kext
- LucyRTL8125Ethernet.kext
- SMCSuperIO.kext
- SMCProcessor.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext
- XHCI-unsupported.kext
- IntelMausi.kext
- AppleMCEReporterDisabler.kext

## Geekbench Results:
- https://browser.geekbench.com/v6/cpu/669382
- https://browser.geekbench.com/v6/compute/242268
- https://browser.geekbench.com/v6/compute/242273

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [Gabriel Luchina - Universo Hackintosh](https://www.youtube.com/@UniversoHackintosh) - for very helpful tips
- tonymacx86.com
