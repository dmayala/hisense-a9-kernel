# hisense-a9-kernel

Mainline Linux support for the Hisense A9 (HLTE556N, SM6115), as a patch series
on top of upstream **Linux v7.2.10** (one snapshot; no private history).

* `patches/`, `patches-gpu/`: apply in order with `git am` onto v7.2.10.
* `patches-pending/`, `candidates/`: not yet in the build.
* `a9*.config`: config fragments. `build.sh`: the build (see README-build.md).
* `initramfs/`: the bring-up initramfs (USB gadget shell, watchdog).

Firmware (GPU, Venus, ADSP, Wi-Fi, Bluetooth) and the E Ink waveform are not
included; extract them from your own phone. Licence: GPL-2.0-only (COPYING).
