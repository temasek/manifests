manifests
=========

Local manifests for building temasek unofficial cm builds

Default ROM/Kernel using AOSP 4.8 toolchain

If your kernel cannot support GCC 4.8, you may drop to use
GCC 4.7 for kernel by adding the following line to your
device branch boardconfig.mk

ARM_EABI_TOOLCHAIN := $(ANDROID_BUILD_TOP)/prebuilts/gcc/linux-x86/arm/arm-eabi-4.7/bin
