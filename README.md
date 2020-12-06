# tevo_tornado_tmc_2130_skr_1.4

Marlin config for the BTT SKR 1.4 board using the TMC 2130 stepper motor drivers in SPI mode. Note: This is a 32bit board, AFAIK it can therfore not be flashed using Arduino.

# Requirements

* [VS Code](https://code.visualstudio.com/Download)
* [PlatformIO Extention](https://platformio.org/)
* [Auto Build Marlin](https://marlinfw.org/docs/basics/auto_build_marlin.html)
* TMC 2130 in SPI mode, if not in SPI mode, follow the insrtuction [here](https://github.com/bigtreetech/BIGTREETECH-TMC2130-V3.0/blob/master/TMC2130-V3.0RM.pdf) to put them into. Soldering `CFG4` and `CFG5` and removing the `SPI` resistor.

# Steps

* Download [Marlin](https://marlinfw.org/meta/download/) (the config file is build with 2.0.7.2)
* Extract Marlin 
* Replace the `Configuration.h` and `Configuration_adv.h` at the extracted `Marlin-2.0.x/Marlin` dir
* In the PlatformIO Home view -> Open Project -> `Marlin-2.0.x` root folder

# Further Information

* [Tevo Tornado SKR 1.4 TMC 2209 & Ugrades (Silent Tornado)](https://www.youtube.com/watch?v=d7VG0SZ4aps) / [Thingiverse with Firmware for the TMC 2209](https://www.thingiverse.com/thing:4544391)
