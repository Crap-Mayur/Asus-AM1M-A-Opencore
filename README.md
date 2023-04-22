# OpenCore EFI for AMD Ryzen Hackintosh

## Verified Specification

| **Component**    | **Model**                                  |
| ---------------- | ------------------------------------------ |
| CPU              | AMD Athlon 5150U                           |
| Motherboard      | ASUS AM1M-A                                |
| RAM              | 8GB (4GB x 2)                              |
| GPU              | GT710                                      |
| Audio Chipset    | Still not Fixed                            |
| Ethernet         | Realtek RTL8111                            |
| OS Disk (NVMe)   | HP 128gb ssd sata                          |

**macOS version**: 12.5 & 11.7.5 \
**OpenCore version**: 0.9.0

## Software Compatibility

- Monterey (12.x)
- Big Sur (11.x)
- Catalina (10.15.x)
- Mojave (10.14.x)
- High Sierra (10.13.x)

## Guides

- Creating USB installer: [\*click\*](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/)
- OpenCore configuration: [\*click\*](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html)
- Post-Install: [\*click\*](https://dortania.github.io/OpenCore-Post-Install/)
- Troubleshooting: [\*click\*](https://dortania.github.io/OpenCore-Install-Guide/troubleshooting/troubleshooting.html)
- ACPI patching: [\*click\*](https://dortania.github.io/Getting-Started-With-ACPI/)

If you have any other questions or issues, feel free to ask on [AMD-OSX Discord](https://discord.gg/EfCYAJW) or [Forum](https://forum.amd-osx.com).

## Credits

- [Apple](https://apple.com) for macOS
- [AMD-OSX Developers](https://github.com/AMD-OSX) for kernel patches for AMD CPUs
- [Acidanthera](https://github.com/acidanthera) for OpenCore and most of used kexts
- [Trulyspinach](https://github.com/trulyspinach) for Ryzen power management and monitoring kexts
- [Mieze](https://github.com/Mieze) for RealtekRTL8111 kext
- [DhinakG](https://github.com/USBToolBox) for USBToolBox
- [XLNC](https://github.com/naveenkrdy) for Adobe patches for AMD CPUs and AppleMCEReportedDisabler kext
- [Pavo](https://github.com/Pavo-IM) for research about AppleMCEReportedDisabler in Monterey
- [tomnic](https://www.macos86.it/profile/69-tomnic/) for libfakeintel.dylib used by Adobe patches
- [Dortania](https://github.com/dortania) for OpenCore configuration guides
- [AMD-OSX Community](https://amd-osx.com) for support while making my Hackintosh
- [SocketByte](https://github.com/SocketByte) for README maintenance and being a great friend :)
