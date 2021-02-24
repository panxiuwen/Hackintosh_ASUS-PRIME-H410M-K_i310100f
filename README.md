# ASUS-PRIME-H410M-K-i3-10100f

# Hardware
CPU: Intel Core i3 10100

GPU: UHD Graph 630

Audio Adapter: ?

Gigabit LAN: RealtekRTL8111

# Bios setting

Please follow this steps to set your bios [Tutorial](https://jingyan.baidu.com/article/90bc8fc822c5d8b752640c1c.html).

Fastboot, Legacy USB Support, turned off.

If CSM can't be turned off, use UEFI only to boot is enough.

# Possible errors

If CFG lock is not turned off, the boot code will be stuck in the End RandomSeed+++

If Legacy USB Support is not turned off, the boot code will be stuck in the HID：Legacy shim 2

# Bootloader

Opencore Version: 0.66

System Edition: Mojave is well tested.

# Optional

Change the HD7750 to FirePro M4000 by replacing ID [Tutorial](https://zhuanlan.zhihu.com/p/351441674).

If you want to enter debug mode, please add -v and keepsyms=1 to boot-args

In order to drive R7 260X, add fake id 26669 [Details](https://www.it610.com/article/1304122155595763712.htm).

# Issue

Not yet
