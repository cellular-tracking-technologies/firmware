# Changelog

## [0.6.7] - 2026-06-05 
### Added
### Changed
### Fixed
  - Fixed RTC issue resulting in invalid system clock time.

## [0.6.6] - 2025-09-19
### Added
### Changed
### Fixed
  - Fixed hour-of-day condition error.

## [0.6.5] - 2025-07-09
### Added
### Changed
  - Set default Tx power to 10 dBm.
### Fixed
  - Fixed hot-swappable SD cards.
  - Fixed base directory not being created when new SD card is inserted.

## [0.6.4] - 2024-08-13
### Added
  - Files written to SD card are now inside a directory that corresponds to the unique id of the device.
### Changed
  - Health messages are now transmitted to the CTT SensorStation three times in a row to improve chance of being received.
### Fixed
  - Config updates made by CTT Mobile are now persistent between reboots.
  - Minor bug fixes with logging system.
  
## [0.6.0] - 2024-07-02
### Added
  - Initial release of the project.
### Changed
### Fixed
  - Syncword of Blu detection now has the correct endianness.
