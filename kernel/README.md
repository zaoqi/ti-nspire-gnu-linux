```
ARCH=arm CROSS_COMPILE=arm-none-eabi- make menuconfig
ARCH=arm CROSS_COMPILE=arm-none-eabi- make -j4 zImage
ARCH=arm CROSS_COMPILE=arm-none-eabi- make dtbs
```
