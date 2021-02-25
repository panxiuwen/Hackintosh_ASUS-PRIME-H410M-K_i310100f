# ASUS-PRIME-H410M-K-i3-10100f

# Hardware

CPU: Intel Core i3 10100

GPU: UHD Graph 630

Audio Adapter: Realtek ALC887

Gigabit LAN: RealtekRTL8111

# Bios setting

Please follow this steps to set your bios [Tutorial](https://jingyan.baidu.com/article/90bc8fc822c5d8b752640c1c.html).

Fastboot, Legacy USB Support ,VT, must turned off, the bios has unlock CFGlcok.

CSM can't be turned off if use VGA to boot.

TPM, Serial port must turned off.

# Possible errors

If you install mojava or an older version, please mask your CPUID[Tutorial](https://blog.csdn.net/YUELEI118/article/details/113828244).

Otherwise the boot code will be stuck in the End RandomSeed+++

If Legacy USB Support is not turned off, the boot code will be stuck in the HID：Legacy shim 2

If you stuck in AppleUSB30XHCIPort@ XXXX, please switch to USB2.0 Interface.

# Bootloader

Opencore Version: 0.66

System Edition: Mojave and Catalina is well tested.

# Optional

If you want to disable debug mode, please remove -v and keepsyms=1 to boot-args

# Issue

Mic don't work.
