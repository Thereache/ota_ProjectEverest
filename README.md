# ota_ProjectEverest

Join here for support - 
1. https://t.me/roms_by_kartik
2. https://t.me/thereachebuildchat

## Flashing Guide

1. Unlock Bootloader
2. Reboot Fastboot
3. Flash boot.img -->> fastboot flash boot boot.img
4. Flash dtbo.img -->> fastboot flash dtbo dtbo.img (Optional)
5. Flash vendor_boot.img -->> fastboot flash vendor_boot vendor_boot.img
6. Reboot Recovery -->> fastboot reboot recovery
7. In the recovery, press Apply Update
8. It will wait for sideload
9. Sideload desired ROM file using -->> adb sideload < ROM >
