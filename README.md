<p align="center"><img src="buildroot/share/pixmaps/logo/marlin-outrun-nf-500.png" height="250" alt="MarlinFirmware's logo" /></p>

This repository provides a more or less up to date version of Marlin that can be used with an Ender 3v2 in combination with the Bigtree SKR E3 Mini v3 Board. 

## Hardware

* Ender 3v2
* Microswiss Direct Drive Extruder
* Bigtree SKR E3 Mini v3 Board
* [Briss Hot End Duct with BL Touch](https://cults3d.com/en/3d-model/tool/ender3-v2-dual-40mm-fan-hot-end-duct-fang)

## Notable Changes

* Marlin with Jyers UI
* Unified Bed Leveling
* Maximize Build area to 232x232
* Use TFT Header for additional Enclosure Fan and Thermistor

## Notes

You might want to change some of the settings to match your configuration. Most notable are the sizes of the printable area, travel limits and probe offsets. 
Furthermore you probably will not use the same linear advance, junction deviation, default axis steps and PID settings (bed and hotend) as I do.

To find your PID settings, this guide is quite nice: https://www.3dmakerengineering.com/blogs/3d-printing/pid-tuning-marlin-firmware

## License

Please see the original [repository](https://github.com/MarlinFirmware/Marlin) for any information on the license and contributors.