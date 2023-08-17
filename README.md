# ThinkpadRyzen-3500U-igpu-Hackintosh
Hackintosh Monterey for Ryzen Thinkpad T495 laptop

![image](https://github.com/kefrulz/ThinkpadRyzen-3500U-igpu-Hackintosh/assets/9220848/f760539f-fe7f-4be9-85af-c284438a6f6e)


An OpenCore config for Thinkpad T495 (Ryzen Edition)

OpenCore version: 0.9.3

macOS: 12.6.8

CPU: AMD Ryzen 5 3500U
Display: AMD Radeon Vega 8 (Working on VRAM 2GB)
Network: Intel wireless 8265 / 8275
Hard-disk: Samsung 256 NVME
RAM: 16GB (8GB soldered + 8GB in slot)
Please change MLB/ROM/Serial Number/UUID.

WORKING:
Graphic Acceleration (using NootedRed.kext)
Network
Battery Status
Audio (AppleALC layout-id=11)

Installation instructions: 

Download Open Core Legacy Patcher on another working MAC
Download Monterey
Create the USB installer (skip installing of OCLP Efi)
Download https://github.com/benbaker76/EFI-Agent to mount the EFI
Paste the EFI from this repo inside a EFI Folder (Structure should be EFI>EFI>(OC and OC folders)
Boot from USB
Select Monterey installer (DMG)
Follow Setup
Format Disk as APFS - GUID (if you have issues, just format first to ExFAT - MBR and then to APFS - GUID)
Install MACOS Monterey
Boot again from USB - Select MACOS installer
Do this as many times needed until the Disk name you selected earlier when formatting appeares
Enjoy your Hackintosh :)

Post Install:
Download EFI Agent to mount the EFI
Copy the EFI folder from the USB drive / Download again from here to the Disk EFI


Bios settings:
Enable Secure boot


Not working yet:
Hibernation
Bluetooth
USB Map (not sure 100% - i am still a beginner)
you tell me :)

Happy Hackintoshing
