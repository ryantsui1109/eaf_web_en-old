# Flashing & Erasing

## ***MAY CAUSE DATA LOSING!!!***
## ***MAY CAUSE DATA LOSING!!!***
## ***MAY CAUSE DATA LOSING!!!***  


## <a name="flashimg"></a>Flashing Images (.img, .bin, etc.)
### **NOT FOR SAMSUNG DEVICES!!**  

1. Reboot to bootloader or fastboot mode (use key combos or adb command)
2. Select the partition to flash (or type it your self)
3. Select the image to flash
4. Click "Start Action", and **wait until finished**

## <a name="flashzip"></a>Flashing Zips

Please reboot to bootloader, fastboot, recovery or sideload mode first

In bootloader (fastboot) mode:
1. Select Zip file to flash using "Fastboot update" 
2. Click "Start Action", and **wait until finished**

In recovery or sideload mode
1. Switch to "Recovery" page in EAF
2. Select Zip file to flash in "Sideload Flashable Zip"
3. Click "Start Action", and **wait until finished**

## <a name="erase"></a>Erasing/Formatting Partition

1. Reboot to bootloader or fastboot mode
2. Select the partition to erase/format (or type it your self)
3. If the partiton to erase has filesystem instead of raw format, you can check the "Use format instead of erase". That will send a image with empty filesystem rather than wipe the blocks of the partition
4. Click "Start Action", and **wait until finished**