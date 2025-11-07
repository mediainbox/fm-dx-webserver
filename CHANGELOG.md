# Changelog

## [Unreleased]

### Added
- `respectFirmwareSettings` config flag to preserve firmware EEPROM state on connection
- Web UI option in setup page for firmware settings control

### Fixed
- Frequency override bug: removed hardcoded 87.5 MHz fallback when `enableDefaultFreq` is disabled

### Changed
- Default value for `respectFirmwareSettings` set to `true` (firmware manages settings by default)
