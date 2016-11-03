# hachiko_bsp
BSP build environment for ArchiTech Hachiko board

## Build Instructions
It is recomended that you run these commands in the order below.

### Get toolchain
```
$ ./build.sh buildroot
```

### Build u-boot
```
$ ./build.sh u-boot
```

### Program u-boot into the board using a Segger JLink
```
$ ./build.sh jlink output/u-boot-2015.01/u-boot.bin 0x18000000
```


