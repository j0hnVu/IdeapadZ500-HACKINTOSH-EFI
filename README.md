# LenovoIdeapadZ500-Hackintosh-EFI

**Lenovo Ideapad Z500 Hackintosh**

**REMEMBER TO CHANGE YOUR SMBIOS USING genSMBIOS**

**NOTE**: THIS GIT IS LIKELY TO BE ABANDONED AS THE LAPTOP USED FOR THIS PROJECT IS NO LONGER AVAILABLE.

**_Spec:_**
- CPU :                 Intel Core i5-3230M
- GPU :                 Intel HD Graphics 4000
- CHIPSET :             Intel Panther Point HM76, Intel Ivy Bridge
- Touchpad :            ELAN input device (LPC)
- Keyboard :            HID Keyboard Device
  	                    Standard PS/2 Keyboard
- AudioCodec :          Realtek ALC269 @ Intel Panther Point PCH - High Definition Audio Controller
- WIFI :               	DW1510 BCM94322HM8L
- Ethernet :            Realtek RTL8139/810x Fast Ethernet Adapter
- Drive :               YGC-SA3-120G YinChu SATA3 120GB SSD

**_Small note:_**
- If you have the same spec, Mojave is the best option imo. Catalina and Big Sur is usable (and beautiful) but they sometimes feel laggy.
- Also, I need to play CS1.6 so Mojave it is!

**_Version installed_**:
* Mojave : [v1.3](https://github.com/j0hnVu/IdeapadZ500-HACKINTOSH-EFI/releases/tag/v1.3)
* Catalina : [v1.3](https://github.com/j0hnVu/IdeapadZ500-HACKINTOSH-EFI/releases/tag/v1.3) 
* Big Sur : [v2.0](https://github.com/j0hnVu/IdeapadZ500-HACKINTOSH-EFI/releases/tag/v2.0)
* Monterrey : **COMING SOON**

**_Tutorial_**

_Preparation:_
* MAC OS (offline or online) installer USB
* Minitool Partition Wizard (FREE)
* Explorer++ (FREE)
* EFI folder can be found in the [Release section](https://github.com/j0hnVu/IdeapadZ500-HACKINTOSH-EFI/releases)

**_Installation:_** 
1.  Assign letter the EFI partition 
* Open Minitool Partition Wizard on the installer USB
* Find FAT32 partition (~100MB) on your USB drive
* Right click on the partition, select "Assign letter", and choose the letter (e.g I:)
* Click APPLY
2.  Copy the EFI folder to the installer USB
* Open Explorer++
* Open EFI partition (I: aforementioned)
* Copy and paste the EFI folder into the partition
3.  Restart and boot to the USB.
4.  Open Disk Utility 
5.  Erase the drive or partition you wish to install Mac OS on
6.  Install MAC OS

_Adding Opencore boot option(Thanks to @big-stiff):_
- If your BIOS supports adding new boot entry, you can set with the path below
> EFI/Boot/BOOTx64.efi *(Currently using)*
or
> EFI/OC/Opencore.efi
- If your BIOS doesnt, you can easily add by using BOOTICE ( Windows required )
Detailed instruction will soon be provided!

**If you have any question, feel free to contact me:**

- Email:   hoanganh170788@gmail.com
- Discord: ZooLs#5693
- Reddit:  zoolsUwU

I will try my best to answer your question.
