
## 0.2.5 [16th April 2024]

### Added
- Added basic support for STM32U5.  [#3370]
- [T3T1] Added support for T3T1.
- [T3T1] Added `HAPTIC` to test haptic feedback.
- [T2T1, T3T1] Added `TOUCH VERSION` to get version number of touch controller.
- Added `VARIANT READ` to read out result of `VARIANT` command.


## 0.2.4 [20th December 2023]

### Added

- [T2B1] `SEC READ` to read out value of SEC counter.
- [T2B1] Check certificate chain upon `CERTDEV READ`, to block bad Optiga signatures
  from being written to device.

### Fixed

- [T2B1] Improve Optiga metadata handling.

## 0.2.3 [06th October 2023]

### Added
- Started changelog.

### Changed
- [T2B1] Start with all-white screen instead of border.  [#3325]


[#3325]: https://github.com/trezor/trezor-firmware/pull/3325
[#3370]: https://github.com/trezor/trezor-firmware/pull/3370
