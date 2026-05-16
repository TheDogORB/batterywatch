# Changelog

## [Unreleased]

## [0.3.0] - 2026-05-16

### Added
- **KDE Connect integration** — monitor battery levels of your paired KDE Connect devices directly from the widget; supports unpair action
- **OpenRazer integration** — Razer wireless peripherals now show battery levels (contributed by @TheDogORB)
- **Appearance settings** — customize font family, font size, and icon size for the tray display (contributed by @TheDogORB)
- **Battery color zones** — set custom colors for charging, warning, and critical battery levels with configurable thresholds (contributed by @TheDogORB)
- **Debug mode** — available in Advanced Settings for troubleshooting (contributed by @TheDogORB)

### Changed
- Disconnect/unpair actions are now owned by each provider — adding new integrations no longer requires touching the main UI
- Configuration naming and labels cleaned up for consistency
- Translations updated and completed for Hebrew, Hungarian, Dutch, and Polish

### Contributors
- @TheDogORB — OpenRazer provider, appearance settings, color zones, debug mode

## [0.2.2] - 2026-03-25

### Changed
- Updated Hungarian translation (by @smileyhead)
- Updated Dutch translation (by @Vistaus)

## [0.2.1] - 2026-03-24

### Added
- **Appearance settings** — customize font and icon sizes for device displays via a new config page
- **Vertical panel support** — device names and battery levels now align correctly when the widget is placed in a vertical panel

### Fixed
- Added device type override for Logitech G Pro X mice (by @xTeixeira)
- Refined OpenLinkHub configuration UI
- Updated Hebrew translation

### Contributors
- @xTeixeira

## [0.2.0] - 2026-02-13

### Added
- **Localization support** — the widget is now fully translatable
- Hungarian translation (by @smileyhead)
- Polish translation (by @AzraelBunn)
- Dutch translation (by @Vistaus)

### Fixed
- Fixed disappearing devices (by @AzraelBunn)

### Contributors
- @smileyhead, @AzraelBunn, @Vistaus

## [0.1.0] - 2025-11-30

Initial development releases (v0.1.0 – v0.1.9, through 2026-01-03). Core functionality: monitor battery levels of Bluetooth and wireless devices via UPower, with OpenLinkHub and BatteryWatch Companion integration.

[Unreleased]: https://github.com/itayavra/batterywatch/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/itayavra/batterywatch/compare/v0.2.2...v0.3.0
[0.2.2]: https://github.com/itayavra/batterywatch/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/itayavra/batterywatch/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/itayavra/batterywatch/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/itayavra/batterywatch/releases/tag/v0.1.0
