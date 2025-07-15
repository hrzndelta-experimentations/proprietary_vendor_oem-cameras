# About
This repository contains stock cameras from blueline (Pixel 3) and sunfish (Pixel 4a) (and maybe some motorola in the future)
# How to include them
- in `/vendor/manufacturer/codename/codename-vendor.mk` add:
```
PRODUCT_PACKAGES += \
    cameraapp
```
Replace:
    manufacturer: your device manufacturer, eg. Google
    codename: your device codename, eg. blueline
    cameraapp: your device stock camera, eg. GoogleCameraBlueline
    
> [!IMPORTANT]
> for GoogleCamera
> These depends on Google Photos and GmsCore (Google's or microG, doesn't matter), as an altenative if you want pure vanilla, you can use [`Gcam-Services-Provider`](https://github.com/lukaspieper/Gcam-Services-Provider)
