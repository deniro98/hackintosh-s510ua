# hackintosh-s510ua
Full Efi for Asus Vivobook S510UA. Works on High Sierra

Catalina Works Cool!

# System specification

    1.Name:           Asus Vivobook S510UA
    2.CPU:            Intel Core i3-7100U
    3.Graphic:        Intel HD Graphics 620 1536 МБ
    4.Wifi:           Intel Dual Band Wireless-AC 8265 - with bluetooth // REPLACED WITH DW1560 (AirDrop and Handoff Working perfectly)
    5.Card Reader:    Realtek_CardReader(RTL8411B_RTS5226_RTS5227)
    6.Camera:         ASUS UVC HD
    7.Audio:          Conexant Audio CX8050
    8.Touchpad:       ELAN1300
    9.Bios Version:   301/303

# Step to install

	0. get wired keyboard and mouse
	1. Replace your EFI to this EFI
	2. Install MAC OS
	3. Reboot.
	4. Move all EFI kexts to /Library/Extensions
	5. Reboot
	6. Touchpad works, gestures works awesome
	
# Run SIRI on S510UA

	1. Gen True SMBIOS and SN Number with Clover Configurator
	2. Install nullethernet.kext from Rehabman
	3. Reboot

# Know problems

    1.  WIFI+BT

