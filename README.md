## Recovery Device Tree for the Samsung Galaxy Tab S6 (Snapdragon)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_gts6l-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_gts6l
