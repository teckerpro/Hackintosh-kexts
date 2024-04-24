# Description
Here is presented common kexts

## Bootloaders
- Clover: [GitHub Slice](https://github.com/CloverHackyColor/CloverBootloader)
- OpenCore: [GitHub Acidanthera](https://github.com/acidanthera/OpenCorePkg)
- Dortania: [Guide](https://dortania.github.io/) [GutHub sources](https://github.com/dortania)
---
## Tools
- MacASL: [GitHub Acidanthera](https://github.com/acidanthera/MaciASL)
- IORegistryExplorer: [GitHub](https://github.com/khronokernel/IORegistryClone/blob/master/ioreg-302.zip)
- GenSMBIOS: [GitHub](https://github.com/corpnewt/GenSMBIOS)
- Hackintool: [GitHub](https://github.com/benbaker76/Hackintool)
---
## Common
- Lilu: [GitHub Acidanthera](https://github.com/acidanthera/Lilu)
- VirtualSMC: [GitHub Acidanthera](https://github.com/acidanthera/VirtualSMC)
- FakeSMC: [GitHub Slice](https://github.com/CloverHackyColor/FakeSMC3_with_plugins)
- RTCMemoryFixup: [GitHub Acidanthera](https://github.com/acidanthera/RTCMemoryFixup)
- HibernationFixup: [GitHub Acidanthera](https://github.com/acidanthera/HibernationFixup)
- NVMeFix (fixing power management and initialization on non-Apple NVMe): [GitHub Acidanthera](https://github.com/acidanthera/NVMeFix)
---
## CPU
Mostly for non native platforms, such as laptops, HEDT, AMD
- ssdtPRgen: [GitHub](https://github.com/Piker-Alpha/ssdtPRGen.sh)
- CPUFriend: [GitHub Acidanthera](https://github.com/acidanthera/CPUFriend)
- CPUFriendFriend: [GitHub](https://github.com/corpnewt/CPUFriendFriend)

The TSC(Time Stamp Counter) is responsible for making sure you're hardware is running at the correct speed, problem is some firmware(mainly HEDT/Server and Asus Laptops) will not write the TSC to all cores causing issues. To get around this, we have 3 options:
- CpuTscSync (for troublesome laptops, HEDT and server motherboards): [GitHub Acidanthera](https://github.com/acidanthera/CpuTscSync)
- VoodooTSCSync (for most HEDT hardware): [BitBucket RehabMan](https://bitbucket.org/RehabMan/voodootscsync/)
- TSCAdjustReset (Skylake X/W/SP and Cascade Lake X/W/SP hardware): [GitHub](https://github.com/interferenc/TSCAdjustReset) or [compiled version](https://github.com/dortania/OpenCore-Install-Guide/blob/master/extra-files/TSCAdjustReset.kext.zip)
---
## Graphics
- WhateverGreen: [GitHub Acidanthera](https://github.com/acidanthera/WhateverGreen)
- Nvidia web driver downloader [GitHub](https://github.com/Benjamin-Dobell/nvidia-update)
---
## LAN Network
- IntelMausi: [GitHub Acidanthera](https://github.com/acidanthera/IntelMausi), [GitHub Mieze](https://github.com/Mieze/IntelMausiEthernet), [Insanelymac Mieze](https://www.insanelymac.com/forum/files/file/396-intelmausiethernet/)
- RealtekRTL8111: [GitHub Mieze](https://github.com/Mieze/RTL8111_driver_for_OS_X), [Insanely Mieze](https://www.insanelymac.com/forum/files/file/88-realtekrtl8111-binary/)
- RealtekLANv3: [GitHub Slice](https://github.com/SergeySlice/RealtekLANv3) [description](https://www.insanelymac.com/forum/topic/286937-realtekr1000-v3/)
- RealtekRTL8100: [GitHub Mieze](https://github.com/Mieze/RealtekRTL8100), [Insanely Mieze](https://www.insanelymac.com/forum/files/file/259-realtekrtl8100-binary/)
- AtherosE2200Ethernet: [GitHub Mieze](https://github.com/Mieze/AtherosE2200Ethernet), [Insanely Mieze](https://www.insanelymac.com/forum/files/file/313-atherose2200ethernet/)
---
## Audio
- AppleALC: [GitHub Acidanthera](https://github.com/acidanthera/AppleALC)
- VoodooHDA: [GitHub Slice](https://github.com/CloverHackyColor/VoodooHDA), [SourceForge](https://sourceforge.net/projects/voodoohda/files/)
---
## USB
- USBMap: [GitHub](https://github.com/corpnewt/USBMap)
- USBToolBox: [GitHub tool](https://github.com/USBToolBox/tool) + [GitHub kext](https://github.com/USBToolBox/kext)
- USBInjectAll (XHCI-unsupported. Temporary kext. Don't use it on based terms): [BitBucket RahabMan](https://bitbucket.org/RehabMan/os-x-usb-inject-all/)
## [Intel Wireless](https://openintelwireless.github.io/)
- itlwm [GitHub OpenIntelWireless](https://github.com/OpenIntelWireless/itlwm)
- IntelBluetoothFirmware [GitHub OpenIntelWireless](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)
