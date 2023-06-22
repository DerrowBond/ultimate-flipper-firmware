<h3 align="center">
</h3>

### Welcome to the Flipper Zero Ultimate Firmware repo! 

<br>

### Most stable custom firmware focused on new features and improvements of original firmware components, with almost no UI changes

<br>

<br>
Our Discord Community:
<br>
<a href="https://discord.gg/jCYQ8C7Z5n"><img src="https://discordapp.com/api/guilds/937479784148115456/widget.png?style=banner4" alt="Ultimate Discord Community" target="_blank"></a>

<br>
<br>
<br>

# What's changed
* Sub-GHz regional TX restrictions removed
* Sub-GHz frequency range can be extended in settings file (Warning: It can damage Flipper's hardware)
* Many rolling code protocols now have the ability to save & send captured signals
* FAAC SLH (Spa) & BFT Mitto (keeloq secure with seed) manual creation
* Sub-GHz static code brute-force plugin
* LFRFID Fuzzer plugin
* Custom community plugins and games added + all known working apps can be downloaded in extra pack in every release
* Extra Sub-GHz frequencies + extra Mifare Classic keys
* Picopass/iClass plugin included in releases
* Recompiled IR TV Universal Remote for ALL buttons
* Universal remote for Projectors, Fans, A/Cs and Audio(soundbars, etc.)
* Customizable Flipper name **Update! Now can be changed in Settings->Desktop** (by @xMasterX and @Willy-JL)
* Text Input UI element -> Cursor feature (by @Willy-JL)
- **BadBT** plugin (BT version of BadKB) [(by Willy-JL, ClaraCrazy, XFW contributors)](https://github.com/ClaraCrazy/Flipper-Xtreme/tree/dev/applications/main/bad_kb) - (See in Applications->Tools) - (aka BadUSB via Bluetooth)
- BadUSB -> Keyboard layouts [(by rien > dummy-decoy)](https://github.com/dummy-decoy/flipperzero-firmware/tree/dummy_decoy/bad_usb_keyboard_layout)
- Sub-GHz -> External CC1101 module support - [(by quen0n)](https://github.com/DarkFlippers/unleashed-firmware/pull/307)
- Sub-GHz -> `Add manually` menu extended with new protocols
- Sub-GHz -> New frequency analyzer - [(by ClusterM)](https://github.com/DarkFlippers/unleashed-firmware/pull/43)
- Sub-GHz -> Save last used frequency [(by derskythe)](https://github.com/DarkFlippers/unleashed-firmware/pull/77)
- Sub-GHz -> Press OK in frequency analyzer to use detected frequency in Read modes [(by derskythe)](https://github.com/DarkFlippers/unleashed-firmware/pull/77)
- Sub-GHz -> Long press OK button in Sub-GHz Frequency analyzer to switch to Read menu [(by derskythe)](https://github.com/DarkFlippers/unleashed-firmware/pull/79)
- Lock device with pin(or regular lock if pin not set) by holding UP button on main screen [(by an4tur0r)](https://github.com/DarkFlippers/unleashed-firmware/pull/107)
* Sub-GHz -> Short press OK in frequency analyzer to save detected frequency for usage in Read modes
* Sub-GHz -> Long press OK button in Sub-GHz Frequency analyzer to switch to Read menu and automatically use selected frequency
* SubGHz -> New option to use timestamps + protocol name when you saving file, instead of random name - Enable in `Radio Settings -> Time in names = ON`
* SubGHz Bruteforcer plugin -> Time delay (between signals) setting (hold Up in main screen(says Up to Save)) + configure repeats in protocols list by pressing right button on selected protocol
* SubGHz -> Read mode UI improvements (scrolling text, + shows time when signal was received) (by @wosk)
* Sub-GHz -> External CC1101 module support (Hardware SPI used)
* SubGHz -> **Hold right in received signal list to delete selected signal**
* SubGHz -> **Custom buttons for Keeloq / Alutech AT4N / Nice Flor S / Somfy Telis / Security+ 2.0 / CAME Atomo** - now you can use arrow buttons to send signal with different button code
* SubGHz -> BFT Mitto / Somfy Telis / Nice Flor S / CAME Atomo, etc.. manual creation with programming new remote into receiver (use button 0xF for BFT Mitto, 0x8 (Prog) on Somfy Telis)
* SubGHz -> Debug mode counter increase settings (+1 -> +5, +10, default: +1)
* SubGHz -> Debug PIN output settings for protocol development
* Infrared -> `RCA` Protocol
* Infrared -> Debug TX PIN output settings
* Other small fixes and changes throughout
* See other changes in readme below



# Instructions
## [- How to install firmware](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/HowToInstall.md)

## [- How to build firmware](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/HowToBuild.md)

## [- How to connect external CC1101 module](https://github.com/quen0n/flipperzero-ext-cc1101)

## [- BadUSB: how to add new keyboard layouts](https://github.com/dummy-decoy/flipperzero_badusb_kl)

## [- How to change Flipper name](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/CustomFlipperName.md)

## [- How to use Mifare Nested plugin to recover keys](https://github.com/AloneLiberty/FlipperNested#how-to-use-it)

## [- How to make captures to add them into Universal IR remotes](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/InfraredCaptures.md)

### **Sub-GHz**

## [- Transmission is blocked? - How to extend Sub-GHz frequency range](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/DangerousSettings.md)

## [- How to add extra Sub-GHz frequencies](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/SubGHzSettings.md)

## [- How to use Flipper as new remote (Nice FlorS, BFT Mitto, Somfy Telis, Aprimatic, AN-Motors, etc..)](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/SubGHzRemoteProg.md)

## [- Configure Sub-GHz Remote App](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/SubGHzRemotePlugin.md)

### **Plugins**

## [- 🎲 Download Extra plugins for Unleashed](https://github.com/xMasterX/all-the-plugins)

## [- TOTP (Authenticator) config description](https://github.com/akopachov/flipper-zero_authenticator/blob/master/docs/conf-file_description.md)

## [- Barcode Generator](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/BarcodeGenerator.md)

## [- Multi Converter](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/MultiConverter.md)

## [- WAV Player sample files & how to convert](https://github.com/UberGuidoZ/Flipper/tree/main/Wav_Player#readme)

## [- Sub-GHz playlist generator script](https://github.com/darmiel/flipper-scripts/blob/main/playlist/playlist_creator_by_chunk.py)

### **Plugins that works with external hardware**

## [- How to use: Unitemp - Temperature sensors reader](https://github.com/quen0n/unitemp-flipperzero#readme)

## [- How to use: [NMEA] GPS](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/applications/external/gps_nmea_uart/README.md)

## [- How to use: i2c Tools](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/applications/external/flipper_i2ctools/README.md)

## [- How to use: [NRF24] plugins](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/NRF24.md)

## [- How to use: [WiFi] Scanner](https://github.com/SequoiaSan/FlipperZero-WiFi-Scanner_Module#readme)

## [- How to use: [ESP8266] Deauther](https://github.com/SequoiaSan/FlipperZero-Wifi-ESP8266-Deauther-Module#readme)

## [- How to use: [ESP32] WiFi Marauder](https://github.com/UberGuidoZ/Flipper/tree/main/Wifi_DevBoard)

## [- [WiFi] Scanner - Web Flasher for module firmware](https://sequoiasan.github.io/FlipperZero-WiFi-Scanner_Module/)

## [- [ESP8266] Deauther - Web Flasher for module firmware](https://sequoiasan.github.io/FlipperZero-Wifi-ESP8266-Deauther-Module/)

## [- Windows: How to Upload .bin to ESP32/ESP8266](https://github.com/SequoiaSan/Guide-How-To-Upload-bin-to-ESP8266-ESP32)

## [- How to use: [GPIO] SentrySafe plugin](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/SentrySafe.md)

<br>
<br>

# Where I can find IR, Sub-GHz, ... files, DBs, and other stuff?
## [UberGuidoZ Playground - Large collection of files - Github](https://github.com/UberGuidoZ/Flipper)
## [Awesome Flipper Zero - Github](https://github.com/djsime1/awesome-flipperzero)

<br>
<br>

# Links

* Ultimate Discord: [https://discord.gg/jCYQ8C7Z5n](https://discord.gg/jCYQ8C7Z5n)
* Hello world - plugin tutorial (English): [https://github.com/DroomOne/Flipper-Plugin-Tutorial](https://github.com/DroomOne/Flipper-Plugin-Tutorial)
* Docs by atmanos / How to write your own app (outdated API): [https://flipper.atmanos.com/docs/overview/intro](https://flipper.atmanos.com/docs/overview/intro)

* Official Docs: [http://docs.flipperzero.one](http://docs.flipperzero.one)

# Project structure

- `applications`    - Applications and services used in firmware
- `assets`          - Assets used by applications and services
- `furi`            - Furi Core: OS-level primitives and helpers
- `debug`           - Debug tool: GDB-plugins, SVD-file and etc
- `documentation`   - Documentation generation system configs and input files
- `firmware`        - Firmware source code
- `lib`             - Our and 3rd party libraries, drivers and etc...
- `site_scons`      - Build helpers
- `scripts`         - Supplementary scripts and python libraries home

Also, pay attention to the `ReadMe.md` files inside those directories.
