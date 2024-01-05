
PixelStar
===========

[**Download**](https://sourceforge.net/projects/pixelstar/files/latest/download)

## Things that will help you getting started ##
- [Pixelstar-devices](https://github.com/Pixelstar-devices)

#### Note ####
- Make sure git-lfs is installed 

### Sync ###

```bash
repo init -u https://github.com/Pixelstar-uday/manifest -b 14 --git-lfs
```

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash
. build/envsetup.sh
lunch aosp_$device-<|userdebug/user/eng|>
mka bacon -jXT
```

## Important Links ##
- [Telegram Announcement Channel](https://t.me/pixelstarchannel)
- [Telegram Discussion Group](https://t.me/Project_PixelStar)

# Credits:

 * [**LineageOS**](https://github.com/LineageOS)
 * [**ParanoidAndroid**](https://github.com/AOSPA)
 * [**crDroid**](https://github.com/crdroidandroid)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**YAAP**](https://github.com/yaap)
 * [**PixysOS**](https://github.com/PixysOS)
 * [**Havoc-OS**](https://github.com/Havoc-OS)
 * [**ColtOS**](https://github.com/Colt-Enigma)

* And tons of other ROMs not mentioned above


## Jai Shri Ram ##
