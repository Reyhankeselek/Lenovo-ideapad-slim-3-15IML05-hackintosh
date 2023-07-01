# Lenovo-ideapad-slim-3-15IML05-hackintosh
Functional, ready to use, perfect efi for lenovo ideapad slim 3 15IML05 HACKINTOSH

But remember to enter your smbios first before using it!

Please to make sure that you have the same model and bios version, but remember : IDEAPAD AND IDEAPAD-SLIM IS NOT THE SAME

model            : LENOVO-IDEAPAD-SLIM-3 15IML05 

Bios             : DXCN44WW 

Cpu              : i3-10110u cometlake-u

Ram              : 4gb micron

Storage          :NVMe SSSTC_CL1-4D256_SSD 256 gb

Wifi adapter     : intel wireless ac 9560

Audio            : realtek audio

If you have lenovo laptop close enough to this model please do not use this efi as is, you have to configure it yourself with dortania open core guide according to your cpu model


# https://dortania.github.io/OpenCore-Install-Guide/


# Working :
Wifi(HeliPort),
Sleep,
Keyboard,
Screen brightness,
Audio,
Usb port (all),
Camera,
Bluetooth,
Battery status,
Headphone jack,
Display brightness hotkey,
Mousepad / trackpad,

# Not working :
Powerbutton (can only be used for wakeing from sleep only)


# Not tested :
Hdmi port,
Sd card reader,


# How to use :

Put your smbios in the config.plist

Generate ssdt's with ssdttime : ssdt-EC,ssdt-HPET,ssdt-PNLF.ssdt-RTCAWAC,ssdt-XOSI

Put the generated ssdt's in the EFI>OC>ACPI folder

And after installing mac os : install HeliPort

# Troubleshooting :

1 If it does not boot or it goes to black screen and restarted you can try :

enabling/disabling dsdt (dsdt is disabled by default)

recreate mac os installer


2 If ghostbuster logo appear you can try :

enable verbose mode and googling the error message

try different smbios


3 If kernel panic appears after installing mac os you can try:

setting the date to 2019 and reinstall mac os

configure your bios settings


**And please use this at your own risk!!!**
![Screen Shot 2023-06-27 at 2 57 15 PM](https://github.com/Reyhankeselek/Lenovo-ideapad-slim-3-15IML05-hackintosh/assets/87765920/822387ae-f20f-48c9-a6a6-b55c79d540e4)
![Screen Shot 2023-06-27 at 2 57 25 PM](https://github.com/Reyhankeselek/Lenovo-ideapad-slim-3-15IML05-hackintosh/assets/87765920/559c997d-a550-4218-95ee-bad6256c29d5)
![Screen Shot 2023-06-27 at 2 58 06 PM](https://github.com/Reyhankeselek/Lenovo-ideapad-slim-3-15IML05-hackintosh/assets/87765920/9e3e9e12-0c7b-4f46-a695-cb7c9e17e074)
