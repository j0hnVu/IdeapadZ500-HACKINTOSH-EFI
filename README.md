# LenovoIdeapadZ500-Hackintosh-EFI

**Lenovo Ideapad Z500 Hackintosh**

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

**_Version installed_**:
* Mojave
* Catalina
* Big Sur

**_Tutorial_**

_Preparation:_
* MAC OS (offline or online) installer USB
* Minitool Partition Wizard (FREE)
* Explorer++ (FREE)
* EFI folder can be found in the [Release section](https://github.com/j0hnVu/IdeapadZ500-HACKINTOSH-EFI/releases)

_Installation:_ 
- Assign letter the EFI partition 
* Open Minitool Partition Wizard on the installer USB
* Find FAT32 partition (~100MB) on your USB drive
* Right click on the partition, select "Assign letter", and choose the letter (e.g I:)
* Click APPLY
- Copy the EFI folder to the installer USB
* Open Explorer++
* Open EFI partition (I: aforementioned)
* Copy and paste the EFI folder into the partition
- Restart and boot to the USB.
- Open Disk Utility 
- Erase the drive or partition you wish to install Mac OS on
- Install MAC OS

_Adding Opencore boot option(Thanks to @big-stiff):_
- If your BIOS supports adding new boot entry, you can set with the path below
> EFI/Boot/BOOTx64.efi *(Currently using)*
or
> EFI/OC/Opencore.efi
- If your BIOS doesnt, you can easily add by using BOOTICE ( Windows required )
Detailed instruction will soon be provided!

**If you have any question, feel free to contact me:**

- Email: hoanganh170788@gmail.com
- Discord: ZooLs#4487

I will try my best to answer your question.
