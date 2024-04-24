# Description
Here is presented common kexts

## Bootloaders
##### Clover: [GitHub Slice](https://github.com/CloverHackyColor/CloverBootloader)
##### OpenCore: [GitHub Acidanthera](https://github.com/acidanthera/OpenCorePkg)
##### Dortania: [Guide](https://dortania.github.io/) [GutHub sources](https://github.com/dortania)
---
## Tools
##### MacASL: [GitHub Acidanthera](https://github.com/acidanthera/MaciASL)
##### IORegistryExplorer: [GitHub](https://github.com/khronokernel/IORegistryClone/blob/master/ioreg-302.zip)
##### USBMap: [GitHub](https://github.com/corpnewt/USBMap)
##### USBToolBox: [GitHub tool](https://github.com/USBToolBox/tool) + [GitHub kext](https://github.com/USBToolBox/kext)
##### GenSMBIOS: [GitHub](https://github.com/corpnewt/GenSMBIOS)
##### Hackintool: [GitHub](https://github.com/benbaker76/Hackintool)
---
## Common
##### Lilu: [GitHub Acidanthera](https://github.com/acidanthera/Lilu)
##### VirtualSMC: [GitHub Acidanthera](https://github.com/acidanthera/VirtualSMC)
##### FakeSMC: [GitHub Slice](https://github.com/CloverHackyColor/FakeSMC3_with_plugins)
##### RTCMemoryFixup: [GitHub Acidanthera](https://github.com/acidanthera/RTCMemoryFixup)
##### HibernationFixup: [GitHub Acidanthera](https://github.com/acidanthera/HibernationFixup)
##### NVMeFix: [GitHub Acidanthera](https://github.com/acidanthera/NVMeFix)
---
## CPU
##### CPUFriend: [GitHub Acidanthera](https://github.com/acidanthera/CPUFriend)

The TSC (Time Stamp Counter) is responsible for ensuring that your CPU is running at its correct defined speed with the correct cores count. However, on some firmware (mostly HEDT/Server and ASUS Laptops) will not write the TSC to all cores which causes a slowdown and every running process is at extremely slow speed. Due to this, when attempting a clean install, the system may enter the boot loop state.
To fix this issue, you can use CpuTscSync or VoodooTSCSync.
##### CpuTscSync: [GitHub Acidanthera](https://github.com/acidanthera/CpuTscSync)
##### VoodooTSCSync: [BitBucket RehabMan](https://bitbucket.org/RehabMan/voodootscsync/)
---
## Graphics
##### WhateverGreen: [GitHub Acidanthera](https://github.com/acidanthera/WhateverGreen)
##### Nvidia web driver downloader [GitHub](https://github.com/Benjamin-Dobell/nvidia-update)
---
## LAN Network
##### IntelMausi: [GitHub Acidanthera](https://github.com/acidanthera/IntelMausi), [GitHub Mieze](https://github.com/Mieze/IntelMausiEthernet), [Insanelymac Mieze](https://www.insanelymac.com/forum/files/file/396-intelmausiethernet/)
##### RealtekRTL8111: [GitHub Mieze](https://github.com/Mieze/RTL8111_driver_for_OS_X), [Insanely Mieze](https://www.insanelymac.com/forum/files/file/88-realtekrtl8111-binary/)
##### RealtekLANv3: [GitHub Slice](https://github.com/SergeySlice/RealtekLANv3) [description](https://www.insanelymac.com/forum/topic/286937-realtekr1000-v3/)
##### RealtekRTL8100: [GitHub Mieze](https://github.com/Mieze/RealtekRTL8100), [Insanely Mieze](https://www.insanelymac.com/forum/files/file/259-realtekrtl8100-binary/)
##### AtherosE2200Ethernet: [GitHub Mieze](https://github.com/Mieze/AtherosE2200Ethernet), [Insanely Mieze](https://www.insanelymac.com/forum/files/file/313-atherose2200ethernet/)
---
## Audio
##### AppleALC: [GitHub Acidanthera](https://github.com/acidanthera/AppleALC)
##### VoodooHDA: [SourceForge](https://sourceforge.net/projects/voodoohda/files/), [GitHub](https://github.com/chris1111/VoodooHDA-2.9.2-Clover-V14/releases)
---
## USB (Temporary kext. Don't use it on based terms!)
##### USBInjectAll: [BitBucket RahabMan](https://bitbucket.org/RehabMan/os-x-usb-inject-all/)
