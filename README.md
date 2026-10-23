# openiboot-mobile
# OpeniBoot Mobile

An experimental ARM64 bootloader and device-porting research project exploring whether the HackiOS iOS 16.5 environment can run on compatible Android hardware.

> **Status: Early research.** The Motorola Moto G(60) XT2135-2 is our first investigation target. It is not currently supported, and no successful iOS boot has been demonstrated on it.

## Goals

- Investigate device-specific boot support for Android phones.
- Use the HackiOS XNU project as an upstream research reference.
- Start with the Motorola Moto G(60) (XT2135-2).
- Develop a reproducible, device-specific build process.
- Prefer emulator testing and non-destructive experiments.
- Consider additional devices only after individual validation.

## Initial target

| Property | Value |
|---|---|
| Manufacturer | Motorola |
| Model | Moto G(60) |
| Model number | XT2135-2 |
| Target OS research | iOS 16.5 |
| Device status | Research only |

## Upstream project

https://github.com/oosexgang/hackios-xnu-kernel

The upstream project is experimental and has device-specific requirements. Its existing boot image must not be assumed compatible with this Motorola.

## Planned milestones

1. Verify hardware, chipset, boot chain, and device tree.
2. Document bootloader and firmware requirements.
3. Investigate XNU, UEFI, and driver compatibility.
4. Establish a reproducible build and test workflow.
5. Test safely before attempting any physical-device boot.
6. Consider other Motorola, Xiaomi, POCO, and OnePlus devices individually.

## Safety

- Do not flash images built for another phone.
- Understand data-wipe consequences before unlocking the bootloader.
- Do not distribute proprietary Apple firmware or system files.
- Keep personal credentials and signing keys out of Git.
- Never describe an untested device as supported.

## Project status

This repository is a community research effort. It does not provide a working universal iOS bootloader or a verified Moto G(60) image yet.

## License

A license will be selected after reviewing the licenses of the upstream code and included components.
