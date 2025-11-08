## AOSP development for the Redmi Note 14 Pro 5G and POCO X7 5G codenamed `malachite`

### Required Hardware/SEPolicy repositories
* [**MediaTek SEPolicy**](https://github.com/mt6878-devs/android_device_mediatek_sepolicy_vndr) (`android_device_mediatek_sepolicy_vndr`)
* [**MediaTek Hardware**](https://github.com/mt6878-devs/android_hardware_mediatek) (`android_hardware_mediatek`)
* [**MediaTek IMS**](https://github.com/mt6878-devs/android_vendor_mediatek_ims) (`android_vendor_mediatek_ims`)
* [**Xiaomi Hardware**](https://github.com/mt6878-devs/android_hardware_xiaomi) (`android_hardware_xiaomi`)

### Required patches
* [**For fixing mediaserver crash after Android 16**](https://github.com/mt6878-devs/android_frameworks_av/commit/283f6151a83541ff5a262e02d053ecf76486a4d2) (`android_frameworks_av`)
* [**For adding support for MTK GED KPI to fix broken gpufreq**](https://github.com/mt6878-devs/android_frameworks_native/commit/ecee0b5e925a4d57313c0f46390fb23997526dec) (`android_frameworks_native`)
* [**MediaTek changes for wpa_supplicant_8**](https://github.com/Nothing-2A/android_external_wpa_supplicant_8/commit/39200b6c7b1f9ff1c1c6a6a5e4cd08c6f526d048) (`android_external_wpa_supplicant_8`)
* [**Enable WAPI for wpa_supplicant_8**](https://github.com/Nothing-2A/android_external_wpa_supplicant_8/commit/37a6e255d9d68fb483d12db550028749b280509b) (`android_external_wpa_supplicant_8`)

### Optional patches (for 60FPS video recording in Aperture)
* [**Aperture**](https://github.com/Nothing-2A/android_packages_apps_Aperture/commit/a4c34aa57ed56de60f29349a1e6d20cf8160ca15) (`android_packages_apps_Aperture`)
