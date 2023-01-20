## Recovery Device Tree for the Samsung Galaxy S20+ (Exynos)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_y2s-eng
make recoveryimage
```

Kernel source:
https://github.com/Nico170420/android_kernel_samsung_universal9830
