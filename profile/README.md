## AOSP development for the Redmi Note 14 Pro 5G and POCO X7 5G codenamed `malachite`

### Required Hardware/SEPolicy repositories
* [**Dolby Atmos**](https://github.com/mt6878-devs/android_packages_apps_XiaomiDolby) (`android_packages_apps_XiaomiDolby`)
* [**MediaTek SEPolicy**](https://github.com/mt6878-devs/android_device_mediatek_sepolicy_vndr) (`android_device_mediatek_sepolicy_vndr`)
* [**MediaTek Hardware**](https://github.com/mt6878-devs/android_hardware_mediatek) (`android_hardware_mediatek`)
* [**MediaTek IMS**](https://github.com/mt6878-devs/android_vendor_mediatek_ims) (`android_vendor_mediatek_ims`)
* [**Xiaomi Hardware**](https://github.com/mt6878-devs/android_hardware_xiaomi) (`android_hardware_xiaomi`)

### Required patches
* [**For fixing mediaserver crash after Android 16**](https://github.com/mt6878-devs/android_frameworks_av/commit/283f6151a83541ff5a262e02d053ecf76486a4d2) (`android_frameworks_av`)
* [**For fixing dolby service crash**](https://github.com/mt6878-devs/android_frameworks_av/commit/11abeca32a66da21fd78ed2d2657b05c58c45b32) (`android_frameworks_av`)
* [**For avoiding SW DAP effects suspend**](https://github.com/mt6878-devs/android_frameworks_av/commit/6fdacd8030e16a51b610cb0143074ac0cc15282a) (`android_frameworks_av`)
* [**Aperture**](https://github.com/Nothing-2A/android_packages_apps_Aperture/commit/a4c34aa57ed56de60f29349a1e6d20cf8160ca15) (`android_packages_apps_Aperture`)
