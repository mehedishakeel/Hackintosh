# AMD Ryzen Hackintosh ( Ryzentosh )
A Hackintosh is a computer that runs Apple's Macintosh operating system macOS on Intel based computer hardware that is not authorized for the purpose by Apple & Ryzentosh is a hackintosh computer build using AMD Ryzen based computer. In this AMD Ryzen hackintosh build i use OpenCore to multiboot Windows(11) and MacOS(Ventura) Olarila Vanila Images.

## Disclaimer
Please Use My Ryzentosh EFI at your own risk. I take no responsiblity if your rig explodes. Create unique SMBios values for your rig. Don't use ones shown in the my efi config.plist!!!

## Watch Full Video About My Hackintosh on YouTube
[![alt text](https://img.youtube.com/vi/aGJ1zKec2T8/maxresdefault.jpg)](https://youtu.be/aGJ1zKec2T8)

## My Mac Pro (Hackintosh) About Screenshot
<img src="screenshot/3.png" alt="3.png"/>

## Specification

| Component        | Model                                              |
| ---------------- | ---------------------------------------------------|
| CPU              | AMD Ryzen 7 3700X                                  |
| MotherBoard      | MSI B450 Mortar MAX                          |
| OS Disk          | Samsung Nano Evo Plus 250 GB NVME SSD              |
| RAM              | 4 X 8 GB Corsair Vengeance Pro 32GB Ram              |
| GPU              | AMD Radeon RX 5600 XT 6GB                               |
| PS   	   | Antec VP550P          		            |


## Installation Steps

* Download EFI Folder + macOS Ventura Olarila Image + Etcher + Mini Parition Tool + Explorer-Plus-Plus.
* Burn macOS raw Image To USB Drive (32GB) with Etcher
* Mount USB Driver EFI Folder Using Free Parition Wizard Tool
* Replace EFI Folder with My EFI into EFI partition.
* Restart PC & Boot From UEFI USB Drive (USE USB 2.0 PORT)
* Using Disk Utility Erase The Disk (APFS)
* Close Disk Utility & Install macOS Ventura.
* After Install Mount Disk EFI & USB Driver EFI with MountEFI and Replace the Disk EFI Folder with The USB Drive EFI Folder. (Do Not Miss This Step Other Wise Your Hackintosh Will Not Boot Without USB Drive)

## Credits and links

* [OpenCore install guide](https://dortania.github.io/OpenCore-Install-Guide)
* [Oralira Vanilla macOS Ventura ](https://www.olarila.com/topic/6278-olarila-vanilla-images-macos-installer/)
* [Ether Flashing Tool](https://etcher.balena.io)
* [Free Mini Partiton Tool](https://www.partitionwizard.com/free-partition-manager.html)
* [Explorer++](https://explorerplusplus.com/download)

## Thanks!!!
