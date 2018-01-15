TWRP device tree for Xiaomi Redmi 5 Plus (vince)
========================================================

To build:

```sh
make clean
. build/envsetup.sh
lunch omni_vince-userdebug
make recoveryimage -j16


For building TWRP for MSM8953 models only.
