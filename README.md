![banner](https://raw.githubusercontent.com/ProjectZenithAOSP/.github/main/banner/banner.png)

# Project Zenith | Android Open Source Software
An Android Operating System Based On AOSP.

### Requirements
- Around 500GB disk space.
- Around 32GB RAM running Linux.

### Sync our source ###
```bash
repo init -u https://github.com/ProjectZenithAOSP/manifest.git -b 15-qpr1
```
```bash
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

### Build our source ###

- Set up the build environment
```bash
source build/envsetup.sh
```

- Lunch a target
```bash
lunch zenith_$devicecodename-userdebug
```

- To start compiling
```bash
mka zenith -j$(nproc --all)
```
# Official Telegram Chat & Channel :
- [Project Zenith Updates](https://t.me/ProjectZenithUpdates)
- [Project Zenith Chat](https://t.me/ProjectZenithChat)

# Credits:

 * [**Android Open Source Project**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**ParanoidAndroid**](https://github.com/AOSPA)
 * [**crDroid**](https://github.com/crdroidandroid)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**YAAP**](https://github.com/yaap)
 * [**PixysOS**](https://github.com/PixysOS)
 * [**Havoc-OS**](https://github.com/Havoc-OS)
 * [**ColtOS**](https://github.com/Colt-Enigma)
 * [**TheParasiteProject**](https://github.com/TheParasiteProject)
 * [**ThePixelProject**](https://github.com/The-Pixel-Project)
 * [**Horizondroid**](https://github.com/HorizonDroidLab)
 * [**The Clover Project**](https://github.com/The-Clover-Project)
 
* And tons of other ROMs not mentioned above
