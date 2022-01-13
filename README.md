# LenovoIdeapadZ500-Mojave-EFI

**Lenovo Ideapad Z500 Hackintosh**

**_Spec:_**
- CPU :                 Intel Core i5-3230M
- GPU :                 Intel HD Graphics 4000
- CHIPSET :             Intel Panther Point HM76, Intel Ivy Bridge
- Touchpad :            ELAN input device (LPC)
- Keyboard :            HID Keyboard Device
  	                    Standard PS/2 Keyboard
- AudioCodec :          Realtek ALC269 @ Intel Panther Point PCH - High Definition Audio Controller
- WIFI :               	~~Atheros AR9485 Wireless Network Adapter~~
                        DW1510 BCM94322HM8L (Affordable, no bluetooth)
- Ethernet :            Realtek RTL8139/810x Fast Ethernet Adapter
- Drive :               YGC-SA3-120G YinChu SATA3 120GB SSD

**_Version installed_**: Mojave

**_Not working:_**
- Touchpad: kinda buggy, need new kext.

~~**- Bluetooth**: hardware issue~~
> I bought a new Wifi card without bluetooth :<

**_Goal:_**
- Updating to Catalina and Big Sur

~~- Fixing sleep and hibernation~~ Done

~~- Replacing current WIFI card~~ Done _( Need BIOS Modding tho )_

~~- Probably buying a 500GB SSD cause 128gb is not enough~~ Need reconsideration :<

**_Tutorial_**
_Installation:_ Mount the EFI partition and copy the EFI to mentioned partition.
_Adding Opencore boot option(Thanks to @big-stiff):_
- If your BIOS supports adding new boot entry, you can set with the path below
> EFI/Boot/BOOTx64.efi *(Currently using)*
or
> EFI/OC/Opencore.efi
- If your BIOS doesnt, you can easily add by using BOOTICE ( Windows required )
Detailed instruction will soon be provided!


If you have any question, feel free to contact me:
- Email: hoanganh170788@gmail.com
- Discord: ZooLs#4487
I will try my best to answer your question.
