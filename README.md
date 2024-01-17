<<<<<<< HEAD
# m127-T-s6
=======



Exynos 850
==========
a127 a217 m127 f127 a135f

1. Edit makefile to 

CROSS_COMPILE= ~/toolchains/gcc/linux-x86/aarch64/aarch64-linux-android-4.9/bin/aarch64-linux-android-

CC= ~/toolchain/clang/host/linux-x86/clang-r353983c/bin/clang

2. Build

make clean && make mrproper
export PLATFORM_VERSION=11
export ANDROID_MAJOR_VERSION=r
export ARCH=arm64
make physwizz_defconfig
make


