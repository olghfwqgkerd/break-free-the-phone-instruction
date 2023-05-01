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
1. Clear yours banking apps data
2. Add banking app and Google playstore to Magisk's DenyList (make sure the Enfore DenyList toggle is off in Magisk's settings)
3. Download and install the latest version of Shamiko
4. Download and install the latest version of LSPosed()
also install the LSPosed https://play.google.com/store/apps/details?id=org.lsposed.manager
5. Reboot and open the LSPosed app to make sure it is working correctly
6. Download and install the latest version of Hide My Applist(https://play.google.com/store/apps/details?id=com.tsng.hidemyapplist) (HMA) app
7. Enable HMA in LSPosed
8. Reboot and open the HMA app to make sure it is working correctly
9. Follow the following steps to configure hiding in the HMA app:
Select Effective Apps -> Tap on "com.(name of your banking app)" -> Toggle Enable hide
Under the Preference head, tap on Select hide methods -> Check API requests, Intent queries, ID detections -> Tap OK
Under the Template config head, tap on 0 additional apps invisible -> Check Magisk, LSPosed and HMA
10. Tap on the save button on the top right corner of the app
11. Reboot and open your banking app, it shouldn't complain of root anymore!

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
