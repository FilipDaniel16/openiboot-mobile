
# Motorola Moto G(60) — Device Profile

## Device Information

- **Device:** Motorola Moto G(60)
- **Model number:** XT2135-2
- **Android version:** Android 12
- **Architecture target:** ARM64 (to be verified against device specifications)
- **Project codename:** Unverified
- **Bootloader status:** Not checked
- **Device testing:** Research only

## Project Goal

Investigate whether an experimental, open-source bootloader and device-porting project could eventually boot an iOS 16.5-based research environment on this device.

This is an experimental research goal, not a claim that iOS currently runs on the Moto G(60).

## Current Status

- [x] Device model identified
- [x] Android version identified
- [x] Initial project documentation created
- [ ] Verify chipset and hardware specifications
- [ ] Research the boot chain and bootloader requirements
- [ ] Investigate existing ARM64 bootloader projects
- [ ] Determine whether this device is technically suitable
- [ ] Develop and test a device-specific bootloader, if feasible

## Compatibility Notes

Android 12 does not establish compatibility with iOS or with any existing bootloader project.

A successful port would require extensive device-specific engineering, including appropriate kernel support, memory and hardware initialization, drivers, and a compatible boot process.

Do not use images built for other phones. In particular, do not flash images intended for the POCO X5 Pro or any other unsupported device onto this Motorola phone.

## Safety Rules

- Do not unlock the bootloader until the consequences have been researched.
- Do not erase, repartition, or flash device storage during initial research.
- Do not use unverified boot images or firmware.
- Keep personal data backed up before any future device experiments.
- Prefer read-only investigation until device compatibility is established.

## Reference

- Upstream research project: https://github.com/oosexgang/hackios-xnu-kernel
- Main project repository: https://github.com/YOUR-GITHUB-USERNAME/openiboot-mobile

Replace `YOUR-GITHUB-USERNAME` in the reference above with your GitHub username when convenient.

## Disclaimer

This repository documents independent experimental research. It does not currently provide a working iOS 16.5 port for the Motorola Moto G(60), and compatibility has not been established.
