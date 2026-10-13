# Cala's Pokecom BASIC — Development Builds

Public **binary-only** distribution for experimental Cala's Pokecom BASIC firmware on ClockworkPi PicoCalc with Raspberry Pi Pico 2 W (RP2350).

**WARNING: DEVELOPMENT BUILDS.** These UF2 images may not have passed hardware acceptance. They are provided for testing, can contain regressions, and are **not official releases**. Back up SD-card data before updating and retain USB BOOTSEL recovery capability.

## Releases and firmware update

- [Development pre-releases](https://github.com/CalaMaclir/Cala-s-Pokecom-BASIC-Dev-Builds/releases): immutable per-build UF2 images and SHA-256 checksums.
- [`development.json`](development.json): machine-readable pointer to the latest **successfully published** development build. It is created and updated by the trusted development CI publisher.
- [Official releases](https://github.com/CalaMaclir/Cala-s-Pokecom-BASIC/releases): stable firmware and public source.

This repository intentionally contains **no development source code**, internal test fixtures, or private CI history. The source is developed in a separate private repository. Build identification and checksums accompany individual releases.

The future on-device web updater is a separate firmware feature. Publishing `development.json` does not mean that the on-device updater is implemented.

## Distribution policy

Only authenticated maintainer-authorized automation or the repository owner may publish a release. New successful builds use new tags; previously published release assets are never replaced. Releases are marked as **pre-release** and do not indicate hardware acceptance.

Copyright (c) 2026 Cala Maclir. Distributed under the [BSD 3-Clause License](LICENSE). Binary redistribution must preserve the license and disclaimer.
