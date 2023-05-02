# Break free the phone instruction

### System
LineageOS for microG

Marvin W 
https://lineage.microg.org/

### Root 
Magisk

topjohnwu
https://github.com/topjohnwu/Magisk

### Hiding the root

- Enable Zygisk
- Disable zzzzzzenforce DennyList
- Reboot
- Install Shamiko
- Reboote
https://github.com/LSPosed/LSPosed.github.io/releases

lordnakki
https://forum.xda-developers.com/t/guide-howto-use-banking-apps-on-your-rooted-device.4530801/

Shamiko
https://github.com/LSPosed/LSPosed.github.io/releases

LSPosed
https://github.com/LSPosed/LSPosed/releases/latest

## INSTALLATION

- adb reboot bootloader
- fastboot devices
- fastboot flash recovery lineageos_recovery_filename.img
- recovery mode
- Factory Reset full
- Apply Update -> Apply from ADB
- adb sideload lineageos_filename.zip

- REBOOT

- download magisk.app
- change .app to .zip
- recovery mode
- Apply Update -> Apply from ADB
- adb sideload magisk_filename.zip
- yes when signature warning

## UPDATE

- Open Magisk
- Click "Uinstall Magisk"
- Click "Restore Image"
- Open "Settings" -> "System" -> "System update"
- Install update, BUT DON'T CLICK "Restart now" !!!
- Open Magisk
- Click "Magisk - Install"
- Choose "Install to inactive Slot (After OTA)
- Click "LET'S GO"
- Now click "Reboot"
