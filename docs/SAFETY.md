# Device Safety and Testing

## Project status

OpeniBoot Mobile is experimental research. The Motorola Moto G(60) XT2135-2 is not currently a supported HackiOS device.

## Before testing

- Back up important personal data.
- Verify the exact model and image target.
- Read official Motorola bootloader-unlock and recovery documentation.
- Understand that bootloader unlocking commonly erases user data.
- Keep a working stock-firmware recovery path before device modifications.

## Never do these things

- Never flash a boot image built for a different phone.
- Never run unverified commands without understanding them.
- Never share passwords, private keys, authentication tokens, or personal data in GitHub.
- Never distribute proprietary Apple firmware or system files without authorization.
- Never claim a device is supported without reproducible test evidence.

## Preferred development workflow

1. Research hardware and boot-chain compatibility first.
2. Use source review and static checks where possible.
3. Prefer emulator testing before physical hardware.
4. Use non-destructive tests whenever possible.
5. Require a verified, model-specific image and recovery plan before any boot attempt.

## Current restriction

No Motorola-specific boot image has been built or verified. Do not flash the upstream POCO image to the Moto G(60).

## Reporting issues

Include the exact model, software version, steps performed, and relevant non-sensitive logs. Remove personal information and secrets before posting logs.
