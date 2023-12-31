1. Dissasembly device according to https://www.youtube.com/watch?app=desktop&v=yOUOJJ1sMkQ
2. Get balong usb downloader and the file https://github.com/forth32/balong-usbdload/blob/master/usblsafe-5573bs.bin  
   Get it from all the required files: https://mega.nz/#!FGQUnD7b!u8-5gglYL3CtNzso2c4Cj-vrfzcppsQNE0u2STpA128 (https://web.archive.org/web/20231231105327/https://www.hovatek.com/forum/thread-16008.html)
3. Short circuit the device, detect using balong usb downloader.
4. Load usblsafe using balong usb downloader.
5. Download dc-unlocker: https://www.dc-unlocker.com/
6. Flash generic firmware "E5573bs-320 21.110.99.01.00".
   Can be found at https://www.mediafire.com/file/90kvmgz4a0zkum9/Huawei_E5573bs-320_Firmware_21.110.99.01.00.7z
6. Fix EIMI and SN using https://web.archive.org/web/20231231105344/https://www.hovatek.com/forum/thread-18443.html and for SN `AT^SN=16digit serial number` from at https://web.archive.org/web/20231231105440/https://gadgetgurumelville.wordpress.com/2016/11/27/unlock-airtel-4g-hotspot-e5573cs-609/comment-page-2/
7. Flash webui using the same method as with balon usb downloader. webui `Update_WEBUI_17.100.08.00.03_Rndis_V7R2_9x25_V7R11_CPIO.exe` found in "all required files" archive.
   May need to "detect" the device using dc-unlocker for the serial port to come up.
8. For ADB and telnet flash `E5573Bs-320_Update_21.200.15.01.209_M_AT_04.10.rar` from https://web.archive.org/web/20231231105046/https://4pda.to/forum/index.php?showtopic=720040&st=20#entry49959520
9. Disable root password (password: admin) for adb to work.
10. Set bypass battery: https://web.archive.org/web/20231231105036/https://www.hovatek.com/forum/thread-32528.html