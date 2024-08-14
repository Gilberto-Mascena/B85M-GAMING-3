# *EFI OC B85M GAMING-3 macOS Catalina*
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Gilberto-Mascena/B85M-GAMING-3)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Gilberto-Mascena/B85M-GAMING-3/.github%2Fworkflows%2Fbuild.yml)
[![license](https://img.shields.io/github/license/Gilberto-Mascena/B85M-GAMING-3)](https://github.com/Gilberto-Mascena/B85M-GAMING-3?tab=MIT-1-ov-file)
[![GitHub stars](https://img.shields.io/github/stars/Gilberto-Mascena/B85M-GAMING-3)](https://github.com/Gilberto-Mascena/B85M-GAMING-3/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/Gilberto-Mascena/B85M-GAMING-3)](https://github.com/Gilberto-Mascena/B85M-GAMING-3/issues)
[![tag](https://img.shields.io/github/v/release/Gilberto-Mascena/Z390M_GAMING?include_prereleases)](https://github.com/Gilberto-Mascena/B85M-GAMING-3/releases)
![release-date](https://img.shields.io/github/release-date/Gilberto-Mascena/B85M-GAMING-3)
![size](https://img.shields.io/github/repo-size/Gilberto-Mascena/B85M-GAMING-3)

---

## *Operational system*

<img align="right" src="./img/banner.png" alt="photo B85M GAMING 3" width="430">

_**macOS**_  _**Catalina 10.15.7**_

---

_**My Setup**_

---

 - _**Motherboard**_
   - [*B85M Gaming-3*](https://www.gigabyte.com/br/Motherboard/GA-B85M-Gaming-3-rev-10#ov)
 - _**CPU**_
   - *Core I3 4170*
 - _**GPU**_
   - *Intel HD Graphics 4400*
 - _**Memory**_
   - *2x8GB Total 16GB*
 - _**SSD Sata**_
   - *Kingston A400 120GB*
 - _**Network**_
   - *Intel I217-V*

---

<a name="ancora"></a>
## Navigation
- [*What works*](#ancora1)
- [*Screenshot*](#ancora2)
- [*Kexts used, (all Releases)*](#ancora3)
- [*Recommended tools*](#ancora4)
- [*Intel BIOS Settings*](#ancora5)
- [*Thanks*](#ancora6)
- [*License* ](#ancora7)

---

<a id="ancora1"></a>
## *What works*

- [x] *Video (onbord HDMI)*
- [x] *Sound*
- [x] *Network*
- [x] *USB*
- [x] *Sleep*

[Top](#ancora)

---

<a id="ancora2"></a>
## *Screenshot*

![screenshot 2022-06-19 às 19 54 43](https://user-images.githubusercontent.com/103699861/175837721-556d1306-439d-4d54-94ea-f96bef419adb.png) 

---
![about](./img/about.png)
## *Sound*
![sound](./img/sound.png)
## *Wired Network*
![nwtwork](./img/network.png)
## *Hackintool peripherals*
![screenshot 2022-09-07 às 20 44 59](https://user-images.githubusercontent.com/103699861/189007640-4b0ecb58-bf56-4123-945d-c59d5a197017.png)
![peripherals](./img/peripherals.png)
## *Hackintool OpenCore Version*
![opencore-version](./img/opencore-version.png)
## *Hackintool kexts*
![kexts](./img/kexts.png)
## *Hackintool USB port mapping*
![mapping-usb](./img/usb-mapping.png)
[Top](#ancora)

---

<a id="ancora3"></a>
## *Kexts used, (all Releases)*

- *[`WhateverGreen.kext`](https://github.com/acidanthera/WhateverGreen)*
- *[`Lilu.kext`](https://github.com/acidanthera/Lilu)*
- *[`VirtualSMC`](https://github.com/acidanthera/VirtualSMC), only: `VirtualSMC.kext`, `SMCProcessor.kext` and `SMCSuperIO.kext`*.
- *[`IntelMausi.kext`](https://github.com/acidanthera/IntelMausi)*
- *[`CpuTscSync.kext`](https://github.com/acidanthera/CpuTscSync)*
- *[`AppleALC.kext`](https://github.com/acidanthera/AppleALC)*
- *`USBMap.kext`*

[Top](#ancora)

---

<a id="ancora4"></a>
## *Recommended tools*

* Recommendation 1
  * *Use [`GenSMBIOS`](https://github.com/corpnewt/GenSMBIOS), to generate new serials for your SMBIOS in order to avoid conflicts with iServices.*
* Recommendation 2
  * *Use [`ProperTree`](https://github.com/corpnewt/ProperTree), to edit your config.plist.*     
* Recommendation 3
  * *Use [`USBMap`](https://github.com/corpnewt/USBMap), to map your USB ports, starting from OC 0.9.3, they can be mapped with XHCIPortLimit enabled in config.plist + [`USBInjectAll`](https://github.com/Sniki/OS-X-USB-Inject-All/releases).*
* Recommendation 4
  * *Extract your DSDT from windows.*
  * *Use [`SSDTTime`](https://github.com/corpnewt/SSDTTime), to generate your SSDT patches.*    
* Recommendation 5
  * *Use [`MaciASL`](https://github.com/acidanthera/MaciASL), to compile your patches into SSDT.*

[Top](#ancora)

---

<a id="ancora5"></a>
## *Intel BIOS Settings*

- [*OpenCore Install Guide*](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html#intel-bios-settings)

[Top](#ancora)

---

<a id="ancora6"></a>
## *Thanks*

- [*Acidanthera Team*](https://github.com/acidanthera)
- [*CorpNewt*](https://github.com/corpnewt)
- [*CrisHotpatch*](https://t.me/crishotpatch)
- [*Dortania*](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html)
- [*Dicas do Mateus*](https://www.youtube.com/c/DicasdoMateus)
- [*Gabriel Luchina*](https://www.youtube.com/c/GabrielLuchina)
- *And others*

[Top](#ancora)

---

<a id="ancora7"></a>
## *License* 

*The* [*MIT License*](LICENSE.md) (*MIT*)

*Copyright :copyright: 2020*

[Top](#ancora)

---