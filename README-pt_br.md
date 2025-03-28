[Português Brasileiro](https://github.com/Gilberto-Mascena/B85M-GAMING-3/blob/main/README-pt_br.md) |
[English](https://github.com/Gilberto-Mascena/B85M-GAMING-3/blob/main/README.md)

# *EFI OC Gigabyte B85M GAMING-3*

[![Status de Manutenção](https://img.shields.io/badge/Maintained-Yes-brightgreen?style=for-the-badge)](https://GitHub.com/Gilberto-Mascena/B85M-GAMING-3)
[![GitHub Actions Status](https://img.shields.io/github/actions/workflow/status/Gilberto-Mascena/B85M-GAMING-3/build.yml?style=for-the-badge)](https://github.com/Gilberto-Mascena/B85M-GAMING-3/actions)
[![Licença](https://img.shields.io/github/license/Gilberto-Mascena/B85M-GAMING-3?style=for-the-badge)](https://github.com/Gilberto-Mascena/B85M-GAMING-3/blob/main/LICENSE.md)
[![Estrelas no GitHub](https://img.shields.io/github/stars/Gilberto-Mascena/B85M-GAMING-3?style=for-the-badge)](https://github.com/Gilberto-Mascena/B85M-GAMING-3/stargazers)
[![Problemas no GitHub](https://img.shields.io/github/issues/Gilberto-Mascena/B85M-GAMING-3?style=for-the-badge)](https://github.com/Gilberto-Mascena/B85M-GAMING-3/issues)
[![Versão do Repositório](https://img.shields.io/github/v/release/Gilberto-Mascena/B85M-GAMING-3?include_prereleases&style=for-the-badge)](https://github.com/Gilberto-Mascena/B85M-GAMING-3/releases)
![Data de Lançamento](https://img.shields.io/github/release-date/Gilberto-Mascena/B85M-GAMING-3?style=for-the-badge)
![Tamanho do Repositório](https://img.shields.io/github/repo-size/Gilberto-Mascena/B85M-GAMING-3?style=for-the-badge)

---

## *Sistemas operacionais*

<div align="left">  
  <img width="100" src="./img/macos-catalina-icon.png" alt="macOS Catalina icons"> 
  <img width="100" src="./img/macos-big-sur-icon.png" alt="macOS Big Sur icons"> 
  <img width="100" src="./img/macos-monterey-icon.png" alt="macOS Monterey icons">   
</div>

<div>
  <img align="right" src="./img/banner.png" alt="photo B85M GAMING 3" width="430">
</div>

---

_**Minha configuração**_

 - _**Placa mãe**_
   - [*Gigabyte B85M Gaming-3*](https://www.gigabyte.com/br/Motherboard/GA-B85M-Gaming-3-rev-10#ov)
 - _**Versão de BIOS**_
   - *F2*
 - _**CPU**_
   - *Core I3 4170*
 - _**GPU**_
   - *Intel HD Graphics 4400*
> [!NOTE]
> _EFI iGPU somente_

##
   - *RADEON RX 570 RED DRAGON Power Color*
> [!NOTE]
> _EFI dGPU somente_

##

 - _**Memória**_
   - *2x8GB Total 16GB*
 - _**SSD Sata**_
   - *Kingston A400 120GB*
 - _**Rede**_
   - *Intel I217-V*

---

<a name="ancora"></a>

## _Navegação por tópicos_

- [*O que funciona*](#ancora1)
- [*Capturas de telas*](#ancora2)
- [*Kexts usados, (todas releases)*](#ancora3)
- [*Ferramentas recomendadas*](#ancora4)
- [*Configurações de BIOS Intel*](#ancora5)
- [*Agradecimentos*](#ancora6)
- [*Licença* ](#ancora7)

---

<a id="ancora1"></a>

<details><summary><h2>O que funciona 👀</h2></summary>

- [x] *Video (onbord HDMI)*
- [x] *Audio*
- [x] *Rede*
- [x] *USB*
- [x] *Sleep*

[Voltar](#ancora)
</details>

<a id="ancora2"></a>

## Capturas de telas

![screenshot 2022-06-19 às 19 54 43](https://user-images.githubusercontent.com/103699861/175837721-556d1306-439d-4d54-94ea-f96bef419adb.png) 

---
![about](./img/about.png)

<details><summary><h2>Audio 👀</h2></summary>

![sound](./img/sound.png)
</details>

<details><summary><h2>Rede 👀</h2></summary>

![nwtwork](./img/network.png)
</details>

<details><summary><h2>Periféricos 👀</h2></summary>

![screenshot 2022-09-07 às 20 44 59](https://user-images.githubusercontent.com/103699861/189007640-4b0ecb58-bf56-4123-945d-c59d5a197017.png)
![peripherals](./img/peripherals.png)
</details>

<details><summary><h2>Versão do OpenCore 👀</h2></summary>

![opencore-version](./img/opencore-version.png)
</details>

<details><summary><h2>kexts 👀</h2></summary>

![kexts](./img/kexts.png)
</details>

<details><summary><h2>Mapeamento de portas USB 👀</h2></summary>

![mapping-usb](./img/usb-mapping.png)

[Voltar](#ancora)
</details>

<a id="ancora3"></a>

<details><summary><h2>Kexts usados, (todas releases) 👀</h2></summary>

- *[`WhateverGreen.kext`](https://github.com/acidanthera/WhateverGreen)*
- *[`Lilu.kext`](https://github.com/acidanthera/Lilu)*
- *[`VirtualSMC`](https://github.com/acidanthera/VirtualSMC), somente: `VirtualSMC.kext`, `SMCProcessor.kext` e `SMCSuperIO.kext`*
- *[`IntelMausi.kext`](https://github.com/acidanthera/IntelMausi)*
- *[`CpuTscSync.kext`](https://github.com/acidanthera/CpuTscSync)*
- *[`AppleALC.kext`](https://github.com/acidanthera/AppleALC)*
- *`USBMap.kext`*

[Voltar](#ancora)
</details>

<a id="ancora4"></a>

<details><summary><h2>Ferramentas recomendadas 👀</h2></summary>

* Recomendação 1
  * *Use [`GenSMBIOS`](https://github.com/corpnewt/GenSMBIOS), para gerar novos seriais para seu SMBIOS a fim de evitar conflitos com iServices*
* Recomendação 2
  * *Use [`ProperTree`](https://github.com/corpnewt/ProperTree), para editar seu config.plist*     
* Recomendação 3
  * *Use [`USBMap`](https://github.com/corpnewt/USBMap), para mapear suas portas USB, a partir do OC 0.9.3, elas podem ser mapeadas com XHCIPortLimit habilitado em config.plist + [`USBInjectAll`](https://github.com/Sniki/OS-X-USB-Inject-All/releases)*
* Recomendação 4
  * *Extraia seu DSDT do Windows*
  * *Use [`SSDTTime`](https://github.com/corpnewt/SSDTTime), para gerar seus patches SSDT*    
* Recomendação 5
  * *Use [`MaciASL`](https://github.com/acidanthera/MaciASL), para compilar seus patches SSDT no mac*

[Voltar](#ancora)
</details>

<a id="ancora5"></a>

<details><summary><h2>Configurações de BIOS Intel 👀</h2></summary>

- [*OpenCore Install Guide*](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html#intel-bios-settings)

[Voltar](#ancora)
</details>

## 👉 [_Criando o instalador do macOS no Windows ou Linux_](https://github.com/Gilberto-Mascena/How-to-create-a-macOS-installer-without-a-Mac)

<a id="ancora6"></a>

## *Agradecimentos*

- [*Acidanthera Team*](https://github.com/acidanthera)
- [*CorpNewt*](https://github.com/corpnewt)
- [*CrisHotpatch*](https://t.me/crishotpatch)
- [*Dortania*](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html)
- [*Dicas do Mateus*](https://www.youtube.com/c/DicasdoMateus)
- [*Gabriel Luchina*](https://www.youtube.com/c/GabrielLuchina)
- *E outros*

[Voltar](#ancora)

<a id="ancora7"></a>

## *Licença* 

[*Licença MIT*](LICENSE.md) (*MIT*)

### Gilberto | Dev _2020_

[Voltar](#ancora)
