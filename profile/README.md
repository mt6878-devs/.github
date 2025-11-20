## AOSP development for the Redmi Note 14 Pro 5G and POCO X7 5G codenamed `malachite`

### Required Hardware/SEPolicy repositories
* [**MediaTek SEPolicy**](https://github.com/mt6878-devs/android_device_mediatek_sepolicy_vndr) (`android_device_mediatek_sepolicy_vndr`)
* [**MediaTek Hardware**](https://github.com/mt6878-devs/android_hardware_mediatek) (`android_hardware_mediatek`)
* [**MediaTek IMS**](https://github.com/mt6899-rodin/android_vendor_mediatek_ims) (`android_vendor_mediatek_ims`)
* [**Xiaomi Hardware**](https://github.com/mt6878-devs/android_hardware_xiaomi) (`android_hardware_xiaomi`)

### Required patches
* [**WPA3 Fix**](https://github.com/mt6878-devs/android_external_wpa_supplicant_8/commit/080ce1dda760ca3400e92564ece36d4628ac55e8) (`android_external_wpa_supplicant_8`)

### Optional patches (for 60FPS video recording in Aperture)
* [**Aperture**](https://github.com/Nothing-2A/android_packages_apps_Aperture/commit/a4c34aa57ed56de60f29349a1e6d20cf8160ca15) (`android_packages_apps_Aperture`)
