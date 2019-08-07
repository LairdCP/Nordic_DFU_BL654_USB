# Laird Connectivity DFU files for BL654 Zephyr/Nordic SDK USB Dongle 451-00004

This repository contains the signing key for the Laird Connectivity BL654 based USB dongle (451-00004) and corrisponding sample secure bootloader project using the SDK v15.3 (only GCC and SES files have been changed)

Please refer to the documentation on the Laird Connectivity website for details on how to use this.

## 451-00003 smartBASIC USB dongle

Please note that this dongle is **not** compatible with the Zephyr/Nordic SDK nor any of the files present on this repository. The 451-00003 dongle will only run smartBASIC and contains different hardware.

## Help

laird_dongle_public.pem contains the signing key to the open bootloader shipped on the modules by default which is needed to sign a bootloader update image.

sample_sdk_15-3_secure_bootloader contains sample code which is pre-modified (GCC and SES builds only) to use soft blinking and can be dropped directly into the nRF52 SDK (15.3 only) under examples\dfu\secure_bootloader
