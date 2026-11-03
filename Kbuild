# SPDX-License-Identifier: GPL-2.0-only
# Build fogos modules together so modpost resolves board-driver dependencies.
subdir-ccflags-y += -I$(src)/include
obj-m += drivers/mmi_annotate/
obj-m += drivers/mmi_info/
obj-m += drivers/sensors/
obj-m += drivers/input/touchscreen/chipone_tddi_v2_mmi/
obj-m += drivers/input/touchscreen/ilitek_v3_mmi/
obj-m += drivers/misc/utag/
obj-m += drivers/power/mmi-smbcharger-iio/
obj-m += drivers/power/qpnp_adaptive_charge/
# Further modules the stock fogos vendor loads (fingerprint, vibrator, SAR,
# NFC, thermal/relay helpers, FM).
obj-m += drivers/input/misc/fpc_fps_mmi/
obj-m += drivers/input/misc/goodix_fod_mmi/
obj-m += drivers/misc/ldo_vibrator_mmi/
obj-m += drivers/misc/sx937x/
obj-m += drivers/misc/awinic/sarsensor/
obj-m += drivers/nfc/sec_nfc/
obj-m += drivers/misc/mmi_sys_temp/
obj-m += drivers/mmi_relay/
obj-m += drivers/fm/
# Camera sensor rails (fogos-wl286xx.dtsi); stock fogos (5.4) built it in.
obj-m += drivers/regulator/wl2864c/
