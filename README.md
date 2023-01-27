# My Ender 3 Marlin configuration

## How to build

1. Get the Marlin https://github.com/MarlinFirmware/Marlin (2.1.2 as of writing this)
2. Get the archive with config examples (check README in _config/_ there)
3. Get the base example from _Configurations-release-2.1.2/config/examples/Creality/Ender-3/CrealityV427_, copy all files to `Marlin/`
4. Get VS Code, install _PlatformIO_ and _Auto BUild Marlin_ extensions
5. Set `default_envs = STM32F103RE_creality` in _platform.io_

## BLTouch

Added BLTouch 3.1 support on v4.2.7 Creality board with [UBL (Unified Bed Leveling)](https://marlinfw.org/docs/features/unified_bed_leveling.html).
