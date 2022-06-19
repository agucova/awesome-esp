# Awesome ESP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code-of-conduct.md)
A curated list of awesome ESP8266/32 projects and code.

<a href="http://espressif.com/en/products/hardware/esp8266ex/overview"><img src="img/esp8266.jpg" alt="ESP8266" align="left" style="margin-right: 25px" height=150></a>
<a href="http://espressif.com/en/products/hardware/esp32/overview"><img src="https://pbs.twimg.com/profile_images/863510403120222208/rjVOiTe3.jpg" alt="ESP32" align="left" style="margin-right: 25px" height=150></a>
> Both the [ESP8266](http://espressif.com/en/products/hardware/esp8266ex/overview) and the [ESP32](http://espressif.com/en/products/hardware/esp32/overview) are low-cost Wi-Fi microchips with full TCP/IP stack and microcontroller capabilities produced by the Shanghai-based manufacturer Espressif Systems.
> <br/>
> See [Contributing](contributing.md) for information on how to contribute to this list.
> <br/><br/>
---

## Contents
- [Firmware](#firmware)
- [Tools](#tools)
- [Projects](#projects)
  - [Smart Home and IoT](#smart-home-and-iot)
  - [InfoSec](#infosec)
  - [Biomedical](#biomedical)
  - [LoRa](#lora)
  - [Music and Audio](#music-and-audio)
  - [Smartwatches](#smartwatches)
  - [Others](#others)
- [Libraries](#libraries)

## Firmware
- [Espressif AT](http://bbs.espressif.com/) - The default vanilla firmware for the ESP8266.
- [NodeMCU](https://github.com/nodemcu/nodemcu-firmware) - An eLua-based firmware for the ESP8266.
- [ESPBasic](http://www.esp8266basic.com/) - A BASIC firmware for easy and wireless programming, ready for the 8266.
- [MicroPython](https://github.com/micropython/micropython/) - An implemention of Python3 for the ESP8266 and 32.
- [ESP3D](https://github.com/luc-github/ESP3D) - An experimental firmware for 3D Printers, both the ESP32 and 8266.
- [Frankenstein](https://github.com/nekromant/esp8266-frankenstein) - A quick and dirty firmware with cool features for the ESP8266.
- [MongooseOS](https://github.com/cesanta/mongoose-os) - An IoT specific firmware, with both C and JS. Available for the ESP32/8266.
- [DeviceHive](https://devicehive.com/) - A firmware made as a client for DeviceHive's IoT data platform, only for the 8266.
- [RT-Thread](https://github.com/RT-Thread/rt-thread) - Chinese open source firmware available for the ESP32.
- [Sming Framework](https://github.com/SmingHub/Sming) - Superb C/C++ IoT Framework with support for ESP8266 and ESP32.

## Tools
- [ESP Flash Tool](http://espressif.com/en/support/download/other-tools) - The vanilla firmware flasher for both ESP's.
- [Arduino Core/8266](https://github.com/esp8266/arduino) - The Arduino core for the ESP8266.
- [Arduino Core/32](https://github.com/espressif/arduino-esp32) - The other Arduino core for the ESP32.
- [ESPTool](https://github.com/espressif/esptool) - Espressif's command line tool for bootloader comms in both ESP's.
- [ESP-Open-SDK](https://github.com/pfalcon/esp-open-sdk) - An open SDK for the ESP8266.
- [ESPTool-ck](https://github.com/igrr/esptool-ck) - A CLI tool for flashing in the ESP8266.
- [ESPTool-gui](https://github.com/Rodmg/esptool-gui) - A flashing GUI tool based on ESPTool-ck.
- [LuaNode](https://github.com/Nicholas3388/LuaNode) - A lua-only SDK for 32/8266.
- [Tuya-Convert](https://github.com/ct-Open-Source/tuya-convert) - A Wi-Fi firmware flasher ESP8266 that has been pre-loaded with Tuya firmware.
- [NodeMCU Flasher](https://github.com/nodemcu/nodemcu-flasher) - The official flashing tool for the NodeMCU OS.
- [Tasmotizer](https://github.com/tasmota/tasmotizer) - A graphical flashing tool for Tasmota firmware. Can manage Wi-Fi & MQTT settings, modules & templates.
- [Arduino FS Plugin](https://github.com/esp8266/arduino-esp8266fs-plugin) - An Arduino plugin for filesystem uploads in the 8266.
- [PlatformIO](https://github.com/platformio/platformio-core) - Cross Platform IDE and Debugger that supports both the ESP32 and ESP8266.

## Projects
### Smart Home and IoT
- [OpenMQTTGateway](https://github.com/1technophile/OpenMQTTGateway) - An implementation of a multiprotocol MQTT gateway for both ESP's among other devices.
- [ESPHome](https://esphome.io/) - A full-featured system for controlling ESP's through simple yet powerful configuration files and Home Automation systems.
- [Tasmota](https://tasmota.github.io/docs/) - An alternative firmware for Sonoff & other ESP8266/ESP32 devices. Includes a large collection of sensor drivers & integrates with [Home Assistant](https://www.home-assistant.io/) natively or via MQTT.
- [ESPEasy](https://github.com/letscontrolit/ESPEasy) - Easily turn ESP modules into multifunction sensor devices for home automation systems.
- [Sonoff-Homekit](https://github.com/Gruppio/Sonoff-Homekit) - An alternative firmware for Sonoff devices (and other 8266 devices) which allows control through Apple's Homekit.
- [DoorsignEPD](https://github.com/jamct/DoorsignEPD) - A smart doorsign with an E-Paper display using the ESP32.
- [EPaperWeatherDisplay](https://github.com/henri98/esp32-e-paper-weatherdisplay) - A very cute e-ink weather display using the ESP32.
- [HomePoint](https://github.com/sieren/Homepoint) - Control MQTT/HomeKit smart home devices from an ESP32-powered screen.
- [openHASP](https://www.openhasp.com/) - Control your home automation devices from a customizable touchscreen UI connected via MQTT.
- [SuperGreenOS](https://github.com/supergreenlab/SuperGreenOS) - A full-featured home farming automation software for the ESP32.
- [CanAirIO](https://github.com/kike-canaries/canairio_firmware#canairio-firmware) - Citizen science project that uses mobile and fixed stations to measure air quality with ESP32 and smartphones.

### InfoSec
- [ESP32-BLECollector](https://github.com/tobozo/ESP32-BLECollector) - A wardriving device which displays BLE devices and collects data from them, all in a nice screen interface.
- [ESP32Marauder](https://github.com/justcallmekoko/ESP32Marauder) - An integrated suite of offensive and defensive tools for WiFi and Bluetooth.
- [ArduinoPcap](https://github.com/spacehuhn/ArduinoPcap) - A library which allows generation of .pcap files with network traffic, for both ESP's.
- [WiFi Satellite](https://hackaday.io/project/28831-wifi-satellite-34c3) - A giant Wifi "satellite" that can monitor all 14 2.4Ghz channels using, well, 14 ESP32s.
- [ESP8266 Deauther](https://github.com/spacehuhn/esp8266_deauther) - A very cool pseudojammer (deauther) of Wifi networks that uses the ESP8266.
- [PacketMonitor](https://github.com/spacehuhn/PacketMonitor32) - A beautiful OLED monitor for packet activity in a WiFi channel. Two versions for each ESP.
- [WiFiDuck](https://github.com/spacehuhn/WiFiDuck) - A wireless-enabled keystroke injector, analogous, but even more awesome than the Rubber Ducky.
- [ESP8266 Beacon Spam](https://github.com/spacehuhn/esp8266_beaconSpam) - Want to confuse people? This device creates hundreds of fake WiFi networks.
- [DeauthDetector](https://github.com/spacehuhn/DeauthDetector) - A small device that shines a light if it detects a WiFi deauth attack. Made by the same guy as the last six projects.

### Biomedical
- [HeartyPatch](https://heartypatch.protocentral.com/) - A wearable BLE and WiFi connected ECG-HR patch which uses the ESP32.
- [HealthyPi v4](https://www.crowdsupply.com/protocentral/healthypi-v4-unplugged) - An amazing open source vital signs monitor that can monitor ECG, respiration, pulse oximetry and body temperature, all run by an ESP32.

### LoRa

- [Meshtastic](https://www.meshtastic.org/) - ESP32 LoRA boards as secure, long battery life, mesh GPS communicators.
- [ESP32-Paxcounter](https://github.com/cyberman54/ESP32-Paxcounter#esp32-paxcounter) - Wifi & Bluetooth driven, LoRaWAN enabled, battery powered mini Paxcounter built on cheap ESP32 LoRa IoT boards.
- [Disaster Radio](https://disaster.radio/) - A disaster-resilient communications network powered by the sun.

### Music and Audio

- [Alles](https://github.com/bwhitman/alles) - A many speaker distributed music synthesizer using UDP multicast over WiFi, modeled after the alles machine/AMY.
- [ESP32-Radio](https://github.com/Edzelf/ESP32-Radio) - Internet radio based on ESP32, VS1053 and a TFT screen.
- [ESPuino](https://github.com/biologist79/ESPuino) - RFID-controlled music player powered by ESP32.
- [Knobby](https://github.com/quadule/knobby) - A handheld Spotify remote that encourages you to explore unfamiliar music.
- [PedalinoMini](https://github.com/alf45tar/PedalinoMini) - A wireless MIDI pedal controller for guitarists, built with the ESP32.
- [Squeezelite-esp32](https://github.com/sle118/squeezelite-esp32) - Streaming audio receiver with multi-room sync, AirPlay, Bluetooth, hardware buttons, display and more.
- [ThingPulse esp8266-spotify-remote](https://github.com/ThingPulse/esp8266-spotify-remote) - Control your Spotify player from a ESP8266 with color touch display.

### Smartwatches

- [mutantW_V1](https://mutantcybernetics.com/mutantW_V1.html) - An ESP32 based open source smartwatch with 1.7 inch display, WiFi, Bluetooth, NeoPixel and vibration.
- [Open SmartWatch](https://open-smartwatch.github.io/) - A FOSS smartwatch with GPS, an inertial unit and an extremely cool 3D-printed case.
- [StickWatch](https://github.com/eggfly/StickWatch) - A smartwatch module based on the M5Stick, using the ESP32.
- [Watchy](https://watchy.sqfmi.com) - An open source e-paper watch with lots of options for customization.

### Others
- [SoftRF](https://github.com/lyusupov/SoftRF) - A DIY aviation proximity awareness system that can be used in UAV projects.
- [Retro ESP32](https://github.com/retro-esp32/RetroESP32) - An extremely cool launcher for the Odroid Go (with the ESP32), which allows emulating several retro consoles.
- [DroneBridge](https://github.com/DroneBridge/ESP32) - An implementation of DroneBridge, a signal link for drones and UAV's on the ESP32.
- [E-TKT](https://github.com/andreisperid/E-TKT) - An ESP32 powered DIY label maker that mixes both old fashioned and contemporary technology.
- [FreeTouchDeck](https://github.com/DustinWatts/FreeTouchDeck) - Open source touch macropad and stream control deck with built-in web configurator.
- [SmartSpin2k](https://github.com/doudar/SmartSpin2k) - Transform your spin bike into a smart trainer with automatic resistance knob control in fitness apps like Zwift.
- [WirelessPrinting](https://github.com/probonopd/WirelessPrinting) - Print wirelessly from Cura, PrusaSlicer or Slic3r to your 3D printer connected to an ESP module.
- [WLED](https://kno.wled.ge/) - Control many types of RGB(W) LED strips with an ESP8266 or ESP32 over WiFi.

## Libraries
- [Wasm3](https://github.com/wasm3/wasm3) - A lightning fast WebAssembly interpreter designed for embedded devices, compatible with both ESP's.
- [Homie8266](https://github.com/marvinroger/homie-esp8266) - Framework implementation of the Homie protocol for the 8266.
- [ESP-Dash](https://github.com/ayushsharma82/ESP-DASH) - Beautiful and fast framework for creating remote dashboards in the 8266/32. No internet required.
- [ESP_mqtt](https://github.com/tuanpmt/esp_mqtt) - MQTT helper library for the ESP8266.
- [GUIslice](https://github.com/ImpulseAdventure/GUIslice) - A drag and drop GUI framework for several devices and screen controllers. Compatible with 8266 and 32.
- [LVGL](https://lvgl.io) - An open-source graphics library providing everything you need to create embedded GUIs with easy-to-use graphical elements, beautiful visual effects and low memory footprint.
- [MicroWebSrv2](https://github.com/jczic/MicroWebSrv2) - A very powerful MicroPython web server which can be used in the ESP32.
- [IRremoteESP8266](https://github.com/markszabo/IRremoteESP8266) - Emit and receive IR signals in the ESP8266.
- [esphomelib](https://github.com/OttoWinter/esphomelib) - Framework to integrate with HomeAssistant in the 8266.
- [TTS](https://github.com/jscrane/TTS) - A somehow good text to speech library for several Arduino devices, both ESP's included.
- [Free802.11](https://github.com/Jeija/esp32free80211) - Library to emit arbitrary 802.11 signals with the ESP32.
- [Koyn](https://github.com/elkrem/koyn) - A decentralized Bitcoin library for the ESP32 and the ESP8266.
- [TFTLibrary](https://github.com/loboris/ESP32_TFT_library) - TFT compatibility for the ESP32.
- [UTFT-ESP](https://github.com/gnulabis/UTFT-ESP) - UTFT Support for the ESP32/8266.
- [ESPAudio](https://github.com/earlephilhower/ESP8266Audio) - Library for playing a diverse range of audio formats in the ESP8266/ESP32.
- [ESP32-audioI2S](https://github.com/schreibfaul1/ESP32-audioI2S) - Plays mp3, m4a and wav files from SD card or stream via I2S interface.
- [AsyncTCP](https://github.com/me-no-dev/ESPAsyncTCP) - Asynchronous TCP Library for both the 8266 and the 32.
- [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) - Homekit implementation for 8266 on RTOS.
- [HomeSpan](https://github.com/HomeSpan/HomeSpan) - A robust and extremely easy-to-use Arduino library for creating your own ESP32-based HomeKit devices.
- [ESPHelper](https://github.com/ItKindaWorks/ESPHelper) - MQTT and Wi-fi automation-oriented library for the 8266.
- [ESPHelper/32](https://github.com/ItKindaWorks/ESPHelper32) - Port of the ESPHelper library for the 32.
- [ESP8266Wifi](https://github.com/ekstrand/ESP8266wifi) - Simple Arduino Wifi library for the 8266.
- [WiFiESP](https://github.com/bportaluri/WiFiEsp) - Arduino library for Wifi management, client/server for 8266 board.
- [TinyGSM](https://github.com/vshymanskyy/TinyGSM) - A quick and simple Arduino library for interaction with GSM modules which can also control the 8266 through AT commands.
- [mJS](https://github.com/cesanta/mjs) - A lightweight and restricted JS engine that is used by MongooseOS, compatible on the 32 and 8266.
- [ESPUI](https://github.com/s00500/ESPUI) - A simply library for making interactive web interfaces for both ESP's.
- [ESP32 ePaper](https://github.com/loboris/ESP32_ePaper_example) - A full-featured library for using ePaper modules with the ESP32.
- [TinyUPnP](https://github.com/ofekp/TinyUPnP) - A lightweight UPnP IGD library for automatic port forwarding on the 8266 and 32.
- [Esp32SSHClient](https://github.com/J-Rios/Arduino-esp32sshclient) - A library that implements a SSH client in the ESP32.
- [painlessMesh](https://github.com/gmag11/painlessMesh) - A library that takes care of the particulars of creating a simple mesh network using ESP8266 and ESP32 hardware.
- [WifiEspNow](https://github.com/yoursunny/WifiEspNow) - Arduino library for [ESP-NOW](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/network/esp_now.html), a connectionless WiFi communication protocol defined by [Espressif](https://github.com/espressif).
- [go-mcu](https://github.com/matiasinsaurralde/go-mcu) - Golang package for interacting with NodeMCU-based boards.
- [CanAirIO SensorLib](https://github.com/kike-canaries/canairio_sensorlib#canairio-air-quality-sensors-library) - ESP32/8266 library with auto-configuration of multiple PM2.5, CO2 and environment sensors.
- [Dhyara](https://github.com/neel/dhyara) - A C/C++ library for making a Mobile Ad hoc Network (MANET) using ESP Now.
- [LedFx](https://github.com/LedFx/LedFx) - A library for using audio input to create realtime light shows. LedFx can control multiple devices and works great with cheap ESP8266 nodes.
