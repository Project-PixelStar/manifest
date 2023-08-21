# PixelStar #

Welcome to PixelStar, the ultimate AOSP Project built upon the solid foundation of PixelExperience Plus. Our primary goal is simple yet ambitious - to deliver an unparalleled Android experience that's smooth, lag-free, and brimming with delightful customizations and pixel goodies.

### Sync ###

Initialize local repository

```bash
repo init -u https://github.com/Project-PixelStar/manifest -b thirteen
```
Sync

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash
. build/envsetup.sh
lunch aosp_$device-<userdebug/user/eng>
mka bacon -jXT
```

Credits
=======

- [**AOSP**](https://android.googlesource.com)
- [**ArrowOS**](https://github.com/ArrowOS)
- [**LineageOS**](https://github.com/LineageOS)
- [**Superior OS**](https://github.com/SuperiorOS)
- [**crDroid**](https://github.com/crdroid-android)
- [**PixelExperience**](https://github.com/PixelExperience)
- [**Pixys**](https://github.com/PixysOS)
- [**VoidUI**](https://github.com/VoidUI-Tiramisu)
- [**RisingOS**](https://github.com/RisingTechOSS)
- [**Project-404**](https://github.com/P-404)
