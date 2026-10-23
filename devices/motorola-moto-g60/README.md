Motorola Moto G(60) — XT2135-2

Status: Research only — not yet supported.

Device identification

- Manufacturer: Motorola
- Model: Moto G(60)
- Model number: XT2135-2
- Device codename: To be independently verified
- Target: Experimental HackiOS iOS 16.5 environment

Objective

Investigate the feasibility of adapting the HackiOS project to this specific Motorola device.

Upstream reference: https://github.com/oosexgang/hackios-xnu-kernel

Research checklist

- [ ] Verify chipset and hardware revision
- [ ] Verify device codename and device-tree sources
- [ ] Identify bootloader and boot-image format
- [ ] Check official bootloader-unlock eligibility
- [ ] Investigate UEFI and kernel compatibility
- [ ] Identify required hardware drivers and firmware
- [ ] Establish a safe build and recovery plan
- [ ] Validate a device-specific image before any boot attempt

Current limitations

The upstream POCO X5 Pro image is not assumed compatible with this Motorola. No Motorola-specific boot image has been built or tested.

Safety

Do not flash images intended for other devices. Do not unlock the bootloader without understanding the potential data wipe. Prefer non-destructive research and testing.

Support status

Experimental research only. Support will be claimed only after a reproducible successful test.
