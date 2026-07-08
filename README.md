# Card-Jitsu — PS Vita Port

This is an unofficial fan-made port of *Card-Jitsu* based on the Android version (club penguin). This port was made to bring the game to Vita hardware, adapting the original Android build to work properly with PS Vita controls, screen resolution and filesystem.

Built using **VitaSDK**, with the game adapted and packaged as a native PS Vita **VPK**. The port includes Vita-specific changes such as input mapping, file path adjustments, app packaging. liveArea setup and performance

- Runs fine on PS Vita hardware
- Based on the Android version of Card-Jitsu
- Native PS Vita VPK included directly in the release

## Installation

A VPK is provided directly in this release. You do not need to apply an xdelta patch or rebuild the game manually.

1. Download the release files
2. Copy `CardJitsuVita.vpk` to your PS Vita
3. Open VitaShell on your Vita
4. Install `CardJitsuVita.vpk` in ux0
5. Launch Card-Jitsu from the LiveArea

Saves and game data are stored in `ux0:/data/CardJitsu/`. They survive updates and reinstalls as they are separated from the app.

## Notes

This port was made using the vitasdk toolchain and adapted from the Android version to run on PS Vita. Some Android-specific systems were changed or replaced so the game could work properly on Vita hardware, including controls, paths, packaging and performance-related adjustments, Several of the assets were taken from the original game; some were remade by me and by "Themoddermods"
