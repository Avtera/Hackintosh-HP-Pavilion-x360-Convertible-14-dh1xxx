# [SUCCESS] HP Pavilion x360 Convertible 14-dh1xxx
100% Tested.

## Specifications
| Type        | Hardware Model                                     | Status |
| :---        | :---                                               | :---: |
| **CPU**         | Intel Core i5-10210U, QuadCore 3.5 GHz, Comet Lake | ✅ |
| **Memory**      | SK hynix HMA81GS6CJR8N-XN	8 GB DDR4-3200           | ✅ |
| **iGPU**        | Intel® UHD Graphics 630 (1.5 GB) `The Intel site is mentioned the iGPU as "Intel® UHD Graphics for 10th Gen" but it's actually an "Intel® UHD Graphics 630"`| ✅ |
| **Disk**        | INTEL SSDPEKNW512G8H  (512 GB, PCI-E 3.0 x4)       | ✅ |
| **Keyboard**    | Standard PS/2 Keyboard                             | ✅ |
| **Mouse**       | Synaptics PrecisionTouchpad Filter Driver          | ✅ |
| **Webcam**      | HP Wide Vision HD Camera                           | ✅ |
| **Battery**     | 333-1C-3B-A HT03041XL                              | ✅ |
| **Audio**       | Realtek ALC295 `Don't update the AppleALC.kext!`   | ✅ |
| **WiFi**        | Realtek RTL8821CE 802.11ac PCIe Adapter            | ❌ |
| **Bluetooth**   | Realtek Bluetooth 4.2 Adapter                      | ❌ |
| **dGPU**        | NVIDIA GeForce MX130 (GM108)                       | ❌ |
| **Fingerprint** | Synaptics WBDI Fingerprint Reader                  | ❌ |
| **Touchscreen** | HID                                                | ❌ |

A laptop without working WiFi and no built in Ethernet port is a pain in the ass, the solution is using **HoRNDIS 9.2** or **TP-Link TL-WN725N v3 USB WiFi** , but if you are ready to void your product gurantee (or is it already?) just change the internal WiFi to supported one. Head to [Dortania Wireless Buyers Guide](https://dortania.github.io/Wireless-Buyers-Guide/unsupported.html#supported-chipsets).


## BIOS Settings
| Option              | Status                     |
| :---                | :---                       |
| Secure Boot         | Disabled                   |
| Intel SGX           | S/W Controlled or Disabled |

*No other bios option needs to be changed unless you want to*

## Tutorial? at this point do u still need a tutorial? jk!
Just download this repo and copy paste the EFI folder to your EFI partition. 
Dont forget to add a compatible SMBIOS inside the config.plist before booting, [you can follow this guide](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/coffee-lake-plus.html#platforminfo).

## All the thanks goes to
- [Dortania](https://github.com/dortania) for [OpencCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [Acidanthera](https://github.com/acidanthera) and other contributors for [OpenCore](https://github.com/acidanthera/OpenCorePkg) *lol obviously 😂*
- [Dr.NooB](https://github.com/itsdrnoob) for [Mi NoteBook 14 Hackintosh EFI Files](https://github.com/itsdrnoob/Mi-NoteBook-14-Hackintosh)
- [h9419](https://github.com/h9419) for [HP Pavilion 14 bf100 Hackintosh EFI Files](https://github.com/h9419/HP_Pavilion_14_bf100_Hackintosh)
- Last, thanks to anything or anyone that help me build this EFI file, too many to write them down here lol xD

# Enjoy Hackintoshing!
