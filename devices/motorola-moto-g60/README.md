
# Motorola Moto G(60) — Device Profile

## Device Information

- **Device:** Motorola Moto G(60)
- **Model number:** XT2135-2
- **Android version:** Android 12
- **Architecture target:** ARM64 (to be verified)
- **Project codename:** HANOIP (reported; requires verification)
- **Chipset:** Qualcomm Snapdragon 732G (SM7150-AC; requires verification)
- **Bootloader status:** Not checked
- **Device testing:** Research only

## Project Goal

Investigate the feasibility of developing an experimental, open-source bootloader and device-porting project targeting an iOS 16.5-based research environment on the Motorola Moto G(60).

This is a research objective, not a claim that iOS currently runs on this device.

## Current Status

- [x] Device model identified
- [x] Android version identified
- [x] Initial project documentation created
- [x] Device profile created
- [ ] Verify chipset and hardware specifications
- [ ] Verify device codename using reliable device sources
- [ ] Research the device boot chain
- [ ] Investigate existing ARM64 bootloader projects
- [ ] Determine technical feasibility
- [ ] Develop device-specific bootloader components, if feasible
- [ ] Test in a safe environment before considering device testing

## Compatibility Notes

Android 12 does not establish compatibility with iOS or any existing bootloader project.

A successful port would require extensive device-specific engineering, potentially including:

- Bootloader and boot-chain compatibility
- Kernel and hardware initialization
- Memory management
- Display, storage, and input drivers
- Firmware compatibility
- Power management and other device drivers
- A compatible operating environment

The device codename and chipset listed above must be verified before development decisions are made.

Do not use boot images built for other phones. In particular, do not flash images intended for the POCO X5 Pro or any other unsupported device onto this Motorola phone.

## Development Environment

Current development is limited to research and documentation using a mobile phone.

No successful build or device boot has been demonstrated. Building and testing low-level boot components may require a suitable Linux or other compatible development environment.

## Safety Rules

- Do not unlock the bootloader until its consequences have been researched.
- Do not erase, repartition, or flash device storage during initial research.
- Do not use unverified boot images or firmware.
- Keep personal data backed up before any future experiments.
- Prefer read-only investigation until compatibility is established.
- Do not publish proprietary firmware or copyrighted operating-system images without the necessary rights.

## References

- Upstream research project: https://github.com/oosexgang/hackios-xnu-kernel
- Main project repository: https://github.com/YOUR-GITHUB-USERNAME/openiboot-mobile

Replace `FilipDaniel16` with your GitHub username when convenient.

## Disclaimer

This repository documents independent experimental research. It does not currently provide a working iOS 16.5 port for the Motorola Moto G(60).

Hardware compatibility, bootloader compatibility, and the feasibility of running the target environment remain unconfirmed.
