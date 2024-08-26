# *EFI OC Gigabyte B85M GAMING-3*
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Gilberto-Mascena/B85M-GAMING-3)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Gilberto-Mascena/B85M-GAMING-3/.github%2Fworkflows%2Fbuild.yml)
[![license](https://img.shields.io/github/license/Gilberto-Mascena/B85M-GAMING-3)](https://github.com/Gilberto-Mascena/B85M-GAMING-3?tab=MIT-1-ov-file)
[![GitHub stars](https://img.shields.io/github/stars/Gilberto-Mascena/B85M-GAMING-3)](https://github.com/Gilberto-Mascena/B85M-GAMING-3/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/Gilberto-Mascena/B85M-GAMING-3)](https://github.com/Gilberto-Mascena/B85M-GAMING-3/issues)
[![tag](https://img.shields.io/github/v/release/Gilberto-Mascena/Z390M_GAMING?include_prereleases)](https://github.com/Gilberto-Mascena/B85M-GAMING-3/releases)
![release-date](https://img.shields.io/github/release-date/Gilberto-Mascena/B85M-GAMING-3)
![size](https://img.shields.io/github/repo-size/Gilberto-Mascena/B85M-GAMING-3)

---

## *Operating systems*

<div align="left">
  <img src="./img/macos-three-int.png" alt="macOS icons"> 
</div>

<div>
  <img align="right" src="./img/banner.png" alt="photo B85M GAMING 3" width="430">
</div>

---

_**My Setup**_

 - _**Motherboard**_
   - [*Gigabyte B85M Gaming-3*](https://www.gigabyte.com/br/Motherboard/GA-B85M-Gaming-3-rev-10#ov)
 - _**BIOS Version**_
   - *F2*
 - _**CPU**_
   - *Core I3 4170*
 - _**GPU**_
   - *Intel HD Graphics 4400*
> [!IMPORTANT]
> _EFI iGPU only_

##
   - *RADEON RX 570 RED DRAGON Power Color*
> [!IMPORTANT]
> _EFI dGPU only_

##

 - _**Memory**_
   - *2x8GB Total 16GB*
 - _**SSD Sata**_
   - *Kingston A400 120GB*
 - _**Network**_
   - *Intel I217-V*

---

<a name="ancora"></a>
## _Topic navigation_
- [*What works*](#ancora1)
- [*Screenshot*](#ancora2)
- [*Kexts used, (all Releases)*](#ancora3)
- [*Recommended tools*](#ancora4)
- [*Intel BIOS Settings*](#ancora5)
- [*Thanks*](#ancora6)
- [*License* ](#ancora7)

---

<a id="ancora1"></a>

<details><summary><h2>What works</h2></summary>

- [x] *Video (onbord HDMI)*
- [x] *Sound*
- [x] *Network*
- [x] *USB*
- [x] *Sleep*

[Top](#ancora)
</details>

<a id="ancora2"></a>

## Screenshots

![screenshot 2022-06-19 às 19 54 43](https://user-images.githubusercontent.com/103699861/175837721-556d1306-439d-4d54-94ea-f96bef419adb.png) 

---
![about](./img/about.png)

<details><summary><h2>Sound</h2></summary>

![sound](./img/sound.png)
</details>

<details><summary><h2>Ethernet</h2></summary>

![nwtwork](./img/network.png)
</details>

<details><summary><h2>Hackintool peripherals</h2></summary>

![screenshot 2022-09-07 às 20 44 59](https://user-images.githubusercontent.com/103699861/189007640-4b0ecb58-bf56-4123-945d-c59d5a197017.png)
![peripherals](./img/peripherals.png)
</details>

<details><summary><h2>Hackintool OpenCore Version</h2></summary>

![opencore-version](./img/opencore-version.png)
</details>

<details><summary><h2>Hackintool kexts</h2></summary>

![kexts](./img/kexts.png)
</details>

<details><summary><h2>Hackintool USB port mapping</h2></summary>

![mapping-usb](./img/usb-mapping.png)

[Top](#ancora)
</details>

<a id="ancora3"></a>

<details><summary><h2>Kexts used, (all Releases)</h2></summary>

- *[`WhateverGreen.kext`](https://github.com/acidanthera/WhateverGreen)*
- *[`Lilu.kext`](https://github.com/acidanthera/Lilu)*
- *[`VirtualSMC`](https://github.com/acidanthera/VirtualSMC), only: `VirtualSMC.kext`, `SMCProcessor.kext` and `SMCSuperIO.kext`*.
- *[`IntelMausi.kext`](https://github.com/acidanthera/IntelMausi)*
- *[`CpuTscSync.kext`](https://github.com/acidanthera/CpuTscSync)*
- *[`AppleALC.kext`](https://github.com/acidanthera/AppleALC)*
- *`USBMap.kext`*

[Top](#ancora)
</details>

<a id="ancora4"></a>

<details><summary><h2>Recommended tools</h2></summary>

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
</details>

<a id="ancora5"></a>

<details><summary><h2>Intel BIOS Settings</h2></summary>

- [*OpenCore Install Guide*](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html#intel-bios-settings)

[Top](#ancora)
</details>

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

### Gilberto | Dev _2020_

[Top](#ancora)

---