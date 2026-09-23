# Awesome MeshCore [![Awesome list badge](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome MeshCore resources. Pull requests welcome!

MeshCore is a multi-platform system for enabling secure text based
communications utilising LoRa radio hardware. It can be used for off-grid
communication, emergency response & disaster recovery, outdoor activities,
tactical security including law enforcement, private security and also IoT
sensor networks.

## Contents

- [Official Resources](#official-resources)
  - [Social Media](#social-media)
- [Client](#client)
  - [Cross-Platform](#cross-platform)
  - [Android](#android)
  - [iOS and Apple](#ios-and-apple)
  - [Desktop](#desktop)
  - [Web](#web)
  - [Terminal](#terminal)
  - [Other Platforms](#other-platforms)
- [Libraries and SDKs](#libraries-and-sdks)
- [Integrations and Bots](#integrations-and-bots)
- [Self-Hosted Dashboards](#self-hosted-dashboards)
- [Packet Analysis](#packet-analysis)
- [Utilities](#utilities)
- [Firmware and Flashing](#firmware-and-flashing)
  - [Forks and Custom Firmware](#forks-and-custom-firmware)
  - [Flashing and Updating](#flashing-and-updating)
- [Hardware](#hardware)
  - [Supported Devices](#supported-devices)
  - [Pre-built Devices](#pre-built-devices)
  - [DIY Builds](#diy-builds)
  - [Enclosures and Mounts](#enclosures-and-mounts)
- [Maps and Diagnostics](#maps-and-diagnostics)
  - [Maps](#maps)
  - [Diagnostics and Dashboards](#diagnostics-and-dashboards)
  - [RF Planning](#rf-planning)
- [Guides and Learning](#guides-and-learning)
- [Communities](#communities)
  - [Virtual](#virtual)
  - [Australia](#australia)
  - [Austria](#austria)
  - [Belgium](#belgium)
  - [Brazil](#brazil)
  - [Bulgaria](#bulgaria)
  - [Canada](#canada)
  - [Czech Republic](#czech-republic)
  - [Europe](#europe)
  - [Finland](#finland)
  - [France](#france)
  - [Germany](#germany)
  - [Hungary](#hungary)
  - [Ireland](#ireland)
  - [Italy](#italy)
  - [Lithuania](#lithuania)
  - [Netherlands](#netherlands)
  - [New Zealand](#new-zealand)
  - [Norway](#norway)
  - [Poland](#poland)
  - [Portugal](#portugal)
  - [Romania](#romania)
  - [Slovakia](#slovakia)
  - [Spain](#spain)
  - [Sweden](#sweden)
  - [Switzerland](#switzerland)
  - [Ukraine](#ukraine)
  - [United Kingdom](#united-kingdom)
  - [United States](#united-states)

---

## Official Resources

Everything from the official MeshCore project:

- [MeshCore.io](https://meshcore.io/) - The official homepage.
- [Documentation](https://docs.meshcore.io/) - Official docs.
- [Blog](https://blog.meshcore.io/) - Official announcements and releases.
- [MeshCore Web Flasher](https://flasher.meshcore.io/) - Official browser-based firmware flasher for supported devices.
- [MeshCore Map](https://map.meshcore.io/) - Official network map.
- [The FAQ](https://github.com/meshcore-dev/MeshCore/blob/main/docs/faq.md) - Official answers on setup, roles and radio settings.
- [Firmware repository](https://github.com/meshcore-dev/MeshCore) - MIT licensed firmware.

### Social Media

- [Discord](https://meshcore.gg) - Official server.
- [Reddit](https://www.reddit.com/r/meshcore/) - Official subreddit.
- [Facebook group](https://www.facebook.com/groups/meshcore)
- [Mastodon](https://mastodon.social/@meshcore)
- [X](https://x.com/mesh_core)
- [YouTube](https://www.youtube.com/@meshcore-official)

## Client

Grouped by platform. Apps marked 🔒 are closed source.

### Cross-Platform

- [Official app](https://files.liamcottle.net/MeshCore/) 🔒 - Proprietary companion app, also on Google Play and the App Store.
- [KIEKR](https://kiekr.app/) 🔒 - iOS and Android community toolbox app.
- [MeshCore Open](https://github.com/zjs81/meshcore-open) - Open-source Flutter client for mobile and desktop.
- [MeshCore SAR](https://github.com/dz0ny/meshcore-sar) - Offline-first search and rescue app with low-bandwidth voice, images and team tracking.
- [Nelos](https://nelos.app/) 🔒 - iOS and Android app for group messaging and tracking people, pets and belongings, with downloadable offline maps.
- [Offband MeshCore](https://github.com/OffbandMesh/meshcore-client) - Cross-platform client with direct and channel chat.
- [SigurdOS Client](https://github.com/hermes-gadget/SigurdOS-client) - Flutter client forked from MeshCore Open with a pixel-art theme.

### Android

- [meshcore-mobile-app](https://github.com/thatSFguy/meshcore-mobile-app) - Hardened Android client, no Google Play Services required.
- [MeshCore-TEAM](https://play.google.com/store/apps/details?id=com.meshcore.team) 🔒 - Android client focused on group operations.
- [Meshcore-Wardrive-Android](https://github.com/mintylinux/Meshcore-Wardrive-Android) - Flutter wardriving app for mapping coverage.
- [meshGO!](https://play.google.com/store/apps/details?id=com.meshcore.meshgo) 🔒 - Android off-grid messaging client.
- [MeshMapper](https://play.google.com/store/apps/details?id=net.meshmapper.app) 🔒 - Android coverage mapping and wardriving app.
- [meshtrax](https://github.com/venamartin/meshtrax) - Flutter Android client with mapping and messaging.
- [Yours](https://github.com/STCisGOOD/yours-x-lunarcore) - Android encrypted messaging client for LunarCore firmware with onion routing experiments.

### iOS and Apple

- [MeshCore One](https://github.com/Avi0n/MeshCoreOne) - Native Swift client for iOS, iPadOS and macOS.
- [PommeCore](https://github.com/mbedworth/PommeCore) - SwiftUI companion app for Apple platforms.

### Desktop

- [mesh-client](https://github.com/Colorado-Mesh/mesh-client) - Electron desktop client for MeshCore, Meshtastic and Reticulum.
- [MeshApp](https://github.com/smikme/meshapp) - Desktop client for MeshCore and Meshtastic with telemetry views.
- [MeshCore gui](https://github.com/pe1hvh/meshcore-gui) - Native desktop client over BLE, no firmware changes required.
- [MeshCore Insights](https://github.com/BomBefok/MeshcoreInsights) - Desktop dashboard with live maps, telemetry analysis and remote node management.
- [MeshCoreQt](https://github.com/zhrkvl/MeshCoreQt) - Qt desktop client.
- [meshy](https://codeberg.org/sesivany/meshy) - GTK4/libadwaita client for Linux and macOS.
- [PyMeshCoreGUI](https://github.com/bliksemlabs/PyMeshCoreGUI) - Qt6 and Python desktop client.
- [QMeshcoreApp](https://github.com/FelixvdDonk/QMeshcoreApp) - Qt6/QML desktop companion with BLE/serial, map and RX log.

### Web

- [meshcore-web (aXistem)](https://github.com/aXistem-dev/meshcore-web) - Docker-ready browser build of the companion app over BLE or USB.
- [meshcore-web (Vue)](https://github.com/liamcottle/meshcore-web) - Early Vue web client, superseded by the official app.
- [meshcore-webui](https://github.com/adradr/meshcore-webui) - Web UI for managing devices and chatting on the mesh.
- [MeshCorium](https://github.com/PEG4TRON/MeshCorium) - Self-hosted client with a local web interface and hybrid contact system.
- [Mycelium](https://github.com/WattleFoxxo/Mycelium) - Browser client for messaging over serial or BLE.

### Terminal

- [MeshChaTUI](https://github.com/g-d-j-evans/MeschaTUI) - Textual terminal client for Linux with delivery confirmation over serial or BLE.
- [meshtui](https://github.com/ekollof/meshtui) - Textual terminal client with delivery tracking and device management.
- [QTC](https://github.com/initsixdev/QTC) - Old-school terminal client for Linux and macOS.
- [Remote Terminal for MeshCore](https://github.com/MichTronics/Remote-Terminal-for-MeshCore) - Remote terminal for repeaters with packet capture and MQTT.
- [tui-meshcore](https://github.com/guax/tui-meshcore) - Terminal chat client with persistent history and regional presets.

### Other Platforms

- [MeshCore64](https://github.com/swannman/meshcore64) - Commodore 64 chat client over a SwiftLink-compatible serial cartridge.
- [PicoMeshCore](https://github.com/Vigoleis912/PicoMeshCore) - MMBasic companion client for the Raspberry Pi Pico over UART.
- [Roadstr](https://github.com/jooray/roadstr) - Road-event reporting over signed Nostr events with MeshCore as transport.
- [Sestriere](https://github.com/atomozero/Sestriere) - Native Haiku OS client with maps, packet analysis and repeater administration.

## Libraries and SDKs

- [meshcore_py](https://github.com/meshcore-dev/meshcore_py) - Official Python bindings over serial, BLE and TCP.
- [meshcore.js](https://github.com/meshcore-dev/meshcore.js) - Official JavaScript companion radio library.
- [meshcore-cli](https://github.com/meshcore-dev/meshcore-cli) - Official command line interface for nodes.
- [meshcore_client](https://github.com/dz0ny/meshcore_client) - Flutter and Dart implementation of the BLE companion protocol.
- [meshcore_upy](https://github.com/fdlamotte/meshcore_upy) - MicroPython bindings.
- [meshcore-go (meshcore-cz)](https://github.com/meshcore-cz/meshcore-go) - Transport-independent Go SDK over serial, BLE and TCP.
- [meshcore-go](https://github.com/meshcore-go/meshcore-go) - Pure Go protocol implementation.
- [meshcore-packets-java](https://github.com/msmuenchen/meshcore-packets-java) - Java packet encoder and decoder.
- [meshcore-pi](https://github.com/brianwiddas/meshcore-pi) - Python protocol implementation for Raspberry Pi and other Linux hosts.
- [meshcore-rs](https://github.com/andrewdavidmackenzie/meshcore-rs) - Rust port of the Python library.
- [meshcore-ts](https://github.com/dpup/meshcore-ts) - Typed TypeScript client over TCP/WiFi and USB serial.
- [MeshCoreCompanion](https://github.com/SH3D/meshcore_c) - Portable C99 companion protocol library with an Arduino C++ wrapper.
- [MeshCoreKmp](https://github.com/Wavesonics/MeshCoreKmp) - Kotlin Multiplatform library for BLE companion nodes.
- [meshpkt](https://github.com/meshcore-cz/meshpkt) - Pure Go packet codec with identity cryptography and TypeScript WebAssembly bindings.
- [openHop Core](https://github.com/openhop-dev/openhop_core) - Python reimplementation of the protocol and routing stack, with direct SX1262 support.

## Integrations and Bots

- [meshcore-ha](https://github.com/meshcore-dev/meshcore-ha) - Official Home Assistant integration, installable via HACS.
- [Cyclenerd MeshCore Bot](https://github.com/Cyclenerd/meshcore-bot) - Node.js command bot with scheduled repeater status collection.
- [Domoticz MeshCore Plugin](https://github.com/galadril/Domoticz-MeshCore-Plugin) - Exposes nodes, telemetry and messaging as native Domoticz devices.
- [ESPHome MeshCore](https://github.com/netmilk/esphome-meshcore) - ESPHome component turning XIAO nRF52840 boards into managed MeshCore sensor nodes.
- [Mesh-Citadel BBS](https://github.com/taedryn/mesh-citadel) - Citadel-style BBS reachable over the mesh.
- [MeshCore BBS](https://github.com/carsten-walther/MeshCore-BBS) - Store-and-forward bulletin board running on a companion radio.
- [MeshCore Discord Bridge](https://github.com/Hude06/MeshCoreDiscordBridge) - Bidirectional Discord bridge with multi-channel routing and flood protection.
- [MeshCore Email Gateway](https://github.com/MGJ520/MeshCore-Email-Gateway) - Bidirectional SMTP/IMAP gateway with a management API.
- [MeshCore SAME EAS Alerter](https://github.com/Mambo430/MeshCore-SAME-EAS-Alerter) - Forwards SAME emergency alert broadcasts onto the mesh.
- [MeshCore UI for Home Assistant](https://github.com/Ratty7198/MeshCore-HA-UI) - Sidebar dashboard on top of meshcore-ha with chat, contacts and maps.
- [meshcore-bot (Go)](https://github.com/meshcore-go/meshcore-bot) - Lightweight bot in Go.
- [meshcore-bot](https://github.com/agessaman/meshcore-bot) - Python bot with Discord and Telegram bridging plus web viewer.
- [meshcore-discord-relay](https://github.com/yellowcooln/meshcore-discord-relay) - Relays MQTT traffic into Discord channels.
- [meshcore-mcp](https://github.com/dpup/meshcore-mcp) - Model Context Protocol server exposing a node to AI agents.
- [meshcore-mqtt](https://github.com/ipnet-mesh/meshcore-mqtt) - MQTT bridge over serial, BLE or TCP with TLS support.
- [Meshcore-Repeater-MQTT-Gateway](https://github.com/jmead/Meshcore-Repeater-MQTT-Gateway) - Gateway firmware bridging repeaters to MQTT.
- [meshcoretomqtt](https://github.com/Cisien/meshcoretomqtt) - Publishes debug and packet capture output to MQTT.
- [Meshpoint](https://github.com/KMX415/meshpoint) - Raspberry Pi base station using an SX1302/SX1303 LoRa concentrator.
- [MeshRes](https://github.com/bryantkelley/MeshRes) - Streams mesh messages into the Resonite social VR platform.
- [openHop Repeater](https://github.com/openhop-dev/openhop_repeater) - Python repeater daemon for Pi-class and embedded Linux hardware.
- [PokeMesh](https://github.com/IdreesInc/PokeMesh) - Collaborative Pokemon FireRed played through channel commands.
- [Spectra](https://forge.hackers.town/Wrewdison/Spectra) - Rust bridge from MeshCore or Meshtastic radios to the Veilid DHT.
- [Supply Drop BBS](https://supplydrop.meshamerica.com/) - Rust BBS for Raspberry Pi with MeshCore and Meshtastic bridges and a plugin system for other transports.

## Self-Hosted Dashboards

- [CoreScope (Kpa-clawbot)](https://github.com/Kpa-clawbot/CoreScope) - Packet analyzer with MQTT ingest, maps, channel chat and per-node analytics.
- [LiteScope](https://github.com/RikoDEV/litescope) - Lightweight MQTT dashboard for node and telemetry monitoring.
- [mc-webui](https://github.com/MarekWo/mc-webui) - Flask web client with SQLite storage and Docker deployment.
- [MeshCore Beacon](https://github.com/MeshCore-Beacon/beacon-server) - Go collector with PostgreSQL storage, WebSocket streaming and a React frontend.
- [MeshCore MQTT Live Map](https://github.com/yellowcooln/meshcore-mqtt-live-map) - Real-time traffic map with coverage, heat and line-of-sight views.
- [meshcore-hub](https://github.com/ipnet-mesh/meshcore-hub) - Collector, REST API and dashboard backed by PostgreSQL.
- [MeshExplorer](https://github.com/ajvpot/meshexplorer) - Real-time map, chat client and packet analysis.
- [MeshMonitor](https://meshmonitor.org/) - Self-hosted multi-protocol dashboard with maps, telemetry and automation.
- [OverMesh](https://github.com/Slofi/overmesh) - Self-hosted dashboard for MeshCore and Meshtastic.
- [PotatoMesh](https://github.com/l5yth/potato-mesh) - Federated dashboard for local communities with remote ingestors and a public API.
- [pyMC Console](https://github.com/Treehouse-00/pymc_console-dist) - Web dashboard for openHop Repeater with RF statistics and terrain mapping.
- [Remote Terminal for MeshCore (jkingsman)](https://github.com/jkingsman/Remote-Terminal-for-MeshCore) - Power-user terminal with server-side packet capture, bots and MQTT integrations.

## Packet Analysis

- [CoreScope](https://github.com/OKI-Mesh/CoreScope) - Live packet visualisation with replay and channel decryption.
- [Lora Wideband Decoder](https://github.com/persistentcache/Lora-Wideband-Decoder) - SoapySDR wideband intercept receiver for LoRa traffic.
- [MCSim](https://github.com/Brent-A/mcsim) - Deterministic simulation framework for firmware testing.
- [MeshCore Packet Tool](https://github.com/meshcore-cz/meshcore-packet-tool) - Browser workbench for inspecting, decoding and crafting packets.
- [MeshCore Signal Tester](https://github.com/kybl/meshcore-signal-tester) - Web and Android RSSI/SNR analysis with GPS-tagged 3D mapping.
- [meshcore_sim](https://github.com/matthewdgreen/meshcore_sim) - Discrete-event simulator running real firmware routing logic.
- [meshcore-decoder-py](https://github.com/chrisdavis2110/meshcore-decoder-py) - Python packet decoder.
- [meshcore-decoder](https://github.com/michaelhart/meshcore-decoder) - TypeScript packet decoder with full cryptographic support.
- [meshcore-packet-capture](https://github.com/agessaman/meshcore-packet-capture) - Capture packets from a companion radio and publish to MQTT.
- [meshcore-packet-knife](https://github.com/jkingsman/meshcore-packet-knife) - Packet inspection and WebGPU hashtag channel key bruteforcing.
- [meshcore-sim](https://github.com/dpup/meshcore-sim) - Deterministic network simulator for testing without radios.
- [MeshCute](https://github.com/MadScientistCH/meshcute) - Portable BLE, Wi-Fi and receive-only LoRa scanner for the M5Stack Cardputer Adv.
- [wireshark-meshcore](https://github.com/aaronb/wireshark-meshcore) - Wireshark dissector and pcapng converter.
- [YAMPA](https://github.com/guax/YAMPA) - Yet another MeshCore packet analyser.

## Utilities

- [Map Tiles Downloader](https://github.com/tekk/map-tiles-downloader) - Terminal utility for downloading offline OpenStreetMap tiles for mesh apps.
- [MeshCore Proxy](https://github.com/rgregg/meshcore-proxy) - TCP proxy exposing a locally connected companion radio to remote clients.
- [MeshCore Utils](https://github.com/samschlegel/meshcore-utils) - Rust vanity Ed25519 key generator with CUDA or Metal acceleration.
- [MeshCore Web Key Generator](https://github.com/agessaman/meshcore-web-keygen) - Browser-only Ed25519 key generator with custom public-key prefixes.

## Firmware and Flashing

### Forks and Custom Firmware

- [Aurora](https://forge.hackers.town/Wrewdison/Aurora) - Standalone T-Deck firmware with contact management and BLE companion support.
- [BlackJackOS](https://github.com/Robert-Proaps/BlackJackOS-BJOS-) - Portable T-Deck toolbox with an application-oriented standalone interface.
- [chiyocore](https://github.com/kore-signet/chiyocore) - Experimental Rust reimplementation for ESP32 with generated board builds.
- [CubeCell MeshCore](https://github.com/atomozero/CubeCellMeshCore) - Minimal repeater firmware for Heltec CubeCell boards.
- [EastMesh](https://github.com/xJARiD/MeshCore-EastMesh) - MQTT repeater and WiFi companion builds with prebuilt releases.
- [EasySkyMesh](https://github.com/IoTThinks/EasySkyMesh) - Power-saving fork for ultra-low-power repeater and sensor deployments.
- [Fennek](https://github.com/danst0/fennek) - T-Deck Pro firmware adding music, audiobooks and eBooks alongside mesh chat.
- [FieldMesh](https://github.com/TogeriX-hub/FieldMesh) - Fork optimised for festivals, hiking and off-grid events.
- [InkCore](https://codeberg.org/todd-herbert/InkCore) - BLE companion firmware for small e-paper devices with configurable applets.
- [LunarCore](https://github.com/STCisGOOD/lunarcore) - Multi-protocol ESP32-S3 firmware combining MeshCore, Meshtastic and RNode/KISS.
- [MCLite](https://github.com/laserir/MCLite) - Lightweight communicator firmware for the T-Deck Plus and T-Watch Ultra.
- [Meck-P4](https://github.com/pelgraine/Meck-P4) - Port of Meck to the ESP32-P4 based LilyGo T-Display P4.
- [Meck](https://github.com/pelgraine/Meck) - BLE and WiFi companion fork for T-Deck Pro, T-Deck Max and T5 E-Paper S3 Pro.
- [Meshcomod](https://github.com/ALLFATHER-BV/meshcomod) - Companion fork exposing USB, Bluetooth and TCP connectivity simultaneously.
- [MeshCore Cardputer ADV (sosprz)](https://github.com/sosprz/meshcore-cardputer-adv) - Flashable ESP32-S3 UI images for the Cardputer ADV.
- [MeshCore Cardputer ADV (Stachugit)](https://github.com/Stachugit/MeshCore-Cardputer-ADV) - Standalone TFT and keyboard interface for the Cardputer ADV.
- [MeshCore Cardputer-ADV](https://github.com/MultiMote/meshcore-cardputer-adv) - Fork for the M5Stack Cardputer Adv with the Cap LoRa-1262 module.
- [MeshCore Low-Power](https://github.com/dt267/MeshCore-Low-Power-Firmware-For-Heltec-V3-V4) - Deep-sleep Heltec V3/V4 builds with BLE, USB and WiFi in one image.
- [MeshCore mishmesh](https://github.com/burakcan/MeshCore-mishmesh) - On-device UI making a companion radio usable without a paired phone.
- [MeshCore PaperUI](https://github.com/dz0ny/meshcore-paperui) - E-paper handheld firmware with standalone messaging, GPS and maps.
- [MeshCore T-Beam 1W](https://github.com/mintylinux/Meshcore-T-beam-1W-Firmware) - Prebuilt builds for the LilyGo T-Beam 1 Watt.
- [MeshCore Wio Tracker L1 Pro (sosprz)](https://github.com/sosprz/Meshcore-Wio-Tracker-L1-Pro) - On-device companion UI for the Seeed Wio Tracker L1 Pro.
- [MeshCore-Solo](https://github.com/MarekZegare4/MeshCore-Solo) - Companion firmware fork adding offline GPS navigation and GPX export.
- [MeshcoreGRID](https://github.com/Quark1980/MeshcoreGRID) - Touch-first handheld firmware with a standalone GRID interface.
- [MeshCoreNG](https://github.com/MichTronics/MeshCoreNG) - Dutch fork focused on smarter repeaters for larger, busier meshes.
- [MeshCoreTel](https://github.com/VBart/MeshCoreTel-firmware) - Repeater fork of EastMesh with WiFi, HTTPS API, web panel and MQTT.
- [MeshCoreTerm](https://github.com/dabeani/meshcoreterm) - Retro-themed companion firmware with on-screen keyboard and hardware navigation.
- [MeshPunk](https://github.com/PhilMo6/meshpunk) - LVGL and Lua handheld firmware for the LilyGo T-Deck.
- [Offband Mesh](https://github.com/OffbandMesh/meshcore-firmware) - Cross-role firmware enhancements and optimisation.
- [Saitama](https://github.com/868meshbot/Saitama) - Standalone firmware for the LilyGo T-Deck and T-Deck Plus.
- [SigurdOS T-Deck](https://github.com/hermes-gadget/SigurdOS-tdeck) - Launcher-style touch UI for the T-Deck with maps and over-the-air updates.
- [TapTap Firmware](https://github.com/mtoolstec/TapTapFW) - Tracker firmware with canned messages, Morse entry and audible alerts.
- [Trail Mate](https://github.com/vicliu624/trail-mate) - Offline-first navigation handheld firmware with native MeshCore packet paths.
- [Wadamesh](https://github.com/ALLFATHER-BV/wadamesh) - Touch-UI LVGL firmware for T-Deck and Heltec V4 TFT.
- [ZephCore](https://github.com/liquidraver/ZephCore) - Ground-up port of MeshCore from Arduino to the Zephyr RTOS.

### Flashing and Updating

- [Heltec V4.2 Multi-Boot](https://github.com/Finmacjones/HeltecV4.2MultiBoot) - Boot selector that switches between MeshCore, Meshtastic and RNode images.
- [Mesh America Device Configurator](https://meshamerica.com/device-configurator/) - Browser flasher and configurator over Web Serial.
- [Mesh Loader](https://github.com/eliahreeves/mesh-loader) - Dual-boot loader keeping MeshCore and Meshtastic in separate ESP32 partitions.
- [MeshCore Drone Updater](https://github.com/lucidnx/meshcore-drone-updater) - Raspberry Pi service for drive-by or drone-assisted DFU updates of unreachable nodes.
- [MeshCore-OTA-Flasher](https://github.com/Dreikor17/MeshCore-OTA-Flasher) - Windows tool for nRF52840 firmware updates over Bluetooth LE.
- [MeshFirmware](https://github.com/mikecarper/meshfirmware) - Interactive Windows and Linux scripts for selecting, flashing and compiling releases.
- [MeshForge](https://github.com/MeshEnvy/mesh-forge) - Cloud firmware builder and web flasher for LoRa mesh devices.
- [Python Nordic Legacy DFU Tool](https://github.com/recrof/nrf_dfu_py) - Cross-platform nRF51/nRF52 Bluetooth DFU tool with GUI and CLI.
- [XIAO nRF52 Updater](https://github.com/recrof/xiao_nrf52_updater) - Updater firmware that flashes nearby nRF52 nodes over Bluetooth DFU.

## Hardware

### Supported Devices

Compatibility references; check these before buying a board.

- [Mesh America supported hardware](https://wiki.meshamerica.com/books/meshcore/page/supported-hardware-for-meshcore) - Community list of compatible boards and chipsets.
- [mesh-sn.de firmware matrix](https://mesh-sn.de/en/devices/matrix) - Per-device matrix of which MeshCore firmware builds are available.
- [MeshCore Europe devices](https://meshcoreeurope.org/en/devices/) - Multilingual device directory with setup guides.
- [LocalMesh UK devices](https://localmesh.co.uk/devices/) - Device guides for the UK emergency network.

### Pre-built Devices

Sold with MeshCore firmware pre-installed, or with MeshCore selectable at order.

- [Seeed Wio Tracker L1 Pro for MeshCore](https://www.seeedstudio.com/Wio-Tracker-L1-Pro-for-Meshcore-p-6717.html) - Handheld with GPS, OLED display and battery.
- [SenseCAP Solar Node P1 Pro for MeshCore](https://www.seeedstudio.com/SenseCAP-Solar-Node-P1-Pro-for-Meshcore-p-6741.html) - Solar-powered outdoor repeater with GPS.
- [Seeed MeshCore Starter Kit](https://www.seeedstudio.com/MeshCore-Starter-Kit-Ready-to-Use-Off-Grid-Instant-Reliable-Communication.html) - Bundle of a repeater and client nodes ready to deploy.
- [RAK WisMesh Tag (Atlavox)](https://atlavox.com/products/wismesh-tag-meshtastic-meshcore-radio) - IP66 GPS tracker; choose the MeshCore variant when ordering.
- [Elecrow ThinkNode M9](https://www.elecrow.com/thinknode-m9-meshcore-communication-terminal-with-full-keyboard-2-4inch-lcd-esp32-s3-lr1110-gps-2300mah.html) - Standalone communicator with QWERTY keyboard, colour LCD and GPS.
- [LilyGo T-LoRa Pager MeshCore](https://lilygo.cc/products/t-lora-pager-meshcore) - Pocket pager with keyboard, display and LR1121 radio.

### DIY Builds

Open designs with published files (PCB, BOM, STL or detailed build guide).

- [915 MHz Mesh Antenna](https://github.com/ellisgl/915-mesh-antenna) - Stacked collinear antenna with simulation files and build dimensions.
- [bardolf MeshCore Repeater](https://github.com/bardolf/meshcore-repeater) - Solar repeater with FreeCAD enclosure, STL files and full BOM.
- [LoRaMeshNodes](https://github.com/hotwolf/LoRaMeshNodes) - Mobile and solar nodes with OpenSCAD enclosures, STL files and BOMs.
- [MeshCore E22P Repeater](https://github.com/Sukecz/MeshCore-E22P-Repeater) - XIAO ESP32-S3 repeater with an Ebyte E22P module, wiring and firmware.
- [NodakMesh solar repeater build](https://nodakmesh.org/blog/meshcore-solar-repeater-build) - Parts list, solar sizing, weatherproofing and configuration walkthrough.
- [RePeter](https://github.com/robrec/MeshCoreRepeater-RePeter) - Bremen repeater board with Gerbers, schematics, BOM and STEP model.
- [XIAO S3 Dual-Radio Repeater](https://github.com/bouyous/meshcore-xiao-s3-dual-radio-repeater) - Two-radio summit repeater with assembly guide and field test reports.

### Enclosures and Mounts

- ["Ray" Heltec V3 case](https://www.thingiverse.com/thing:7395161) - Handheld case with room for one 18650 cell.
- [Case-Stick for ProMicro nRF52](https://www.thingiverse.com/thing:7394936) - Stick-shaped case for ProMicro nRF52840 boards.
- [The Corebell](https://www.printables.com/model/1490873-the-corebell-a-meshcoremeshtastic-solar-node) - Printable solar node enclosure.
- [Heltec T114 case with battery](https://www.thingiverse.com/thing:7390213) - Compact handheld case with an integrated battery bay.
- [MeshCore mast enclosure for Heltec V3](https://www.printables.com/model/1767610-meshcore-mast-enclosure-heltec-v3) - Mast-mounted outdoor enclosure.
- [NodakMesh enclosures guide](https://nodakmesh.org/meshcore/enclosures) - Overview of commercial and DIY cases with IP-rating guidance.
- [Outdoor Case for MeshCore Node / Repeater](https://www.thingiverse.com/thing:7383479) - Printable weatherproof repeater case.

## Maps and Diagnostics

Tools to see what is happening on the mesh.

### Maps

- [Czech coverage map](https://pokryti.meshcore.cz/) - Czech coverage with terrain-aware planning.
- [HanseMesh map](https://hansemesh.de/netzwerk/karte/) - Northern Germany repeater status and coverage.
- [KernWi-Fi map](https://meshcore.kernwifi.com.au/map) - South Australian repeater and observer network.
- [LocalMesh Germany map](https://localmesh.de/karte/) - German coverage with repeater directory.
- [LocalMesh Netherlands map](https://localmesh.nl/en/map/) - Dutch network coverage.
- [LoraMesh France map](https://loramesh.fr/carte/) - French coverage by region.
- [m3sh.uk Map](https://m3sh.uk/contacts/) - UK network as seen from Oxfordshire.
- [mapme.sh](https://mapme.sh/) - Crowdsourced coverage mapping with companion wardriving apps.
- [MeshCore Europe map](https://meshcoreeurope.org/en/map/) - European repeater and room server coverage.
- [MeshCore Map](https://map.meshcore.dev/) - Static user uploads.
- [MeshCore Polska map](https://mapa.meshcorepolska.org/) - Polish clients, repeaters, room servers and sensors.
- [MeshMapper](https://meshmapper.net/) - Wardriving coverage platform with regional instances and an open API.

### Diagnostics and Dashboards

- [Boston MeshCore MQTT dashboard](https://mcmqttdashboard.bostonme.sh/) - Live MQTT node presence and traffic metrics.
- [EU Meshcore Analyzer](https://meshcore-analyzer.eu/) - Live visual map of European MeshCore LoRa network traffic.
- [KernWi-Fi live telemetry](https://meshcore.kernwifi.com.au/live) - South Australian live activity feed.
- [MeshCore Analyzer (letsmesh)](https://analyzer.letsmesh.net/) - Node connectivity, packet analysis and mesh health metrics.
- [MeshCore Tools](https://meshcore.envoyage.io/) - Repeater configurator and region code lookup helpers.
- [TennMesh Live](https://live.tennmesh.com/) - Tennessee telemetry with RF link analysis and routing loop detection.

### RF Planning

- [contempl8 Relief](https://contempl8.io/tools/relief/) - Free browser 3D terrain block viewer for inspecting the landform around a site; can be slow on large areas.
- [contempl8 Topo](https://contempl8.io/tools/topo/) - Free browser elevation profile along a drawn line, useful for rough line-of-sight checks.
- [MeshKit](https://meshkit.app/) - Browser site planner with terrain LOS, Fresnel analysis and BLE radio tools.
- [MeshOMatic](https://map.meshomatic.net/) - Terrain-aware repeater placement planning and topology analysis.

## Guides and Learning

- [Andy Kirby on YouTube](https://www.youtube.com/@andykirby) - Hardware reviews, repeater builds and firmware walkthroughs.
- [Austin Mesh setup guide](https://www.austinmesh.org/join/meshcore-setup/) - Beginner-friendly local setup.
- [J-Rat Techworks repeater guide](https://jrattechworks.com/meshcore-repeater-flashing-guide/) - Flashing and repeater setup.
- [Kev's Robots MeshCore course](https://www.kevsrobots.com/learn/meshcore/) - Structured tutorial series from basics to flashing.
- [LocalMesh NL setup guide](https://www.localmesh.nl/en/meshcore-setup/) - Dutch-language beginner guide.
- [Mesh America wiki](https://wiki.meshamerica.com/books/meshcore/page/start-here-meshcore-guide) - Guides and protocol overview.
- [Mesh Sorocaba configuração](https://www.meshsorocaba.org/configuracao/) - Portuguese-language setup documentation.
- [MeshCore Europe getting started](https://meshcoreeurope.org/en/get-started/) - Multilingual introduction.
- [MeshCore Europe repeater guide](https://meshcoreeurope.org/en/repeater-guide/) - Repeater deployment walkthrough.
- [MeshCore Ninja](https://meshcore.ninja/) - Open catalog of regional networks, devices, firmwares and software.
- [NodakMesh wiki](https://nodakmesh.org/meshcore/wiki) - Reference documentation and setup guides.
- [WISSEN TECHNIK podcast](https://wissen-technik-meshcore-meshtastic.podigee.io/) - German-language podcast on MeshCore and Meshtastic.

## Communities

### Virtual

- [MeshCore subreddit](https://old.reddit.com/r/meshcore/) - Community discussion.

### Australia

- [EastMesh Australia](https://eastmesh.au/) - Eastern Australia community.
- [MeshCore AUS wiki](https://wiki.meshcoreaus.org/) - Australian community documentation.
- [MeshSydney](https://meshsydney.com/) - Sydney configuration and coordination.
- [NSW Mesh](https://nswmesh.au/) - Sydney and New South Wales network with a community knowledge base.
- [Perth MeshCore](https://perth.meshcore.au/) - Western Australia network.

### Austria

- [CarinthiaMesh wiki](https://wiki.carinthiamesh.com/) - Carinthian regional wiki.
- [MeshCore AT Telegram group](https://t.me/meshcoreat) - Austrian community chat.
- [MeshCore Austria](https://meshcore.at/) - German-language documentation and setup guides.

### Belgium

- [LoraMesh België](https://www.loramesh.be/) - Emergency communication network.
- [MeshCore België](https://meshcore.radio-actief.be/) - Community wiki and setup guides.

### Brazil

- [Mesh Sorocaba](https://www.meshsorocaba.org/) - Portuguese-language guides and community.
- [MeshCore Brasil Telegram group](https://t.me/meshcorebrasil) - Brazilian community chat.

### Bulgaria

- [MeshCore Bulgaria](https://www.meshcore.bg/) - Bulgarian community with map, presets and Telegram group.

### Canada

- [CascadiaMesh](https://cascadiamesh.org/) - Pacific Northwest network spanning British Columbia, Washington and Oregon.
- [MeshCore Canada](https://meshcore.ca/) - National site with provincial communities.
- [Montreal Mesh](https://www.montrealmesh.ca/en/) - Montreal area MeshCore and Meshtastic community.
- [Salish Mesh](https://salishmesh.net/) - Salish Sea region of southwest British Columbia.

### Czech Republic

- [MeshCore ČR](https://meshcore.cz/) - Czech-language community and documentation.

### Europe

- [MeshCore Europe](https://meshcoreeurope.org/) - Multilingual umbrella site with community directory, guides and maps.

### Finland

- [Mesh Pirkanmaa](https://meshpirkanmaa.org/) - Tampere and Pirkanmaa region community.

### France

- [LoraMesh France](https://loramesh.fr/) - French community with regional coverage.
- [MeshCore France](https://www.meshcore.fr/) - French network coordination.
- [MeshCore Paris](https://meshcore.paris/) - Paris and Greater Paris region network.

### Germany

- [HanseMesh](https://hansemesh.de/) - Northern Germany network and tutorials.
- [IsarMesh](https://isarmesh.de/) - Bavarian community forum.
- [LocalMesh Deutschland](https://www.localmesh.de/) - German emergency radio network with guides.
- [Mesh Dresden](https://meshdresden.eu/) - Dresden and wider Saxony community.
- [Mesh Rheinland](https://www.meshrheinland.de/) - Rheinland and western Germany community.
- [MeshCore DE Telegram group](https://t.me/meshcorede) - German community chat.
- [MeshCore Deutschland wiki](https://meshcore-de.fyi/) - German-language wiki hub with setup guides and regional group directory.
- [MeshCore Essen-Kettwig](https://jonathansalim.de/) - Public network around Essen-Kettwig in the Ruhr area.
- [MeshMitte](https://msh3.de/) - Central Germany community.
- [Münsterland Mesh](https://mcml.info/) - Münsterland region of North Rhine-Westphalia.
- [SaarMesh](https://saarmesh.de/) - Saarland regional network.

### Hungary

- [MeshCore Hungary](https://mc868.hu/) - Hungarian community on 868 MHz with map and Telegram group.

### Ireland

- [LoRa Project Ireland](https://loraproject.ie/) - Island of Ireland off-grid messaging community.
- [Mayo Mesh](https://mayomesh.net/#/) - County Mayo mesh radio user group.

### Italy

- [MeshCore ITA Telegram group](https://t.me/meshcore_ita) - Public group, per-region topics.
- [MeshCore ITA](https://meshcore-ita.github.io/) - Italian-language documentation: setup guide, the shared Italian radio preset, hardware, CLI reference, troubleshooting, FAQ and glossary.
- [MeshCore Italia](https://www.meshcoreitalia.it) - Nationwide Italian mesh on the EU/UK narrow preset, with map and Telegram group.

### Lithuania

- [Atviras Tinklas](https://atvirastinklas.lt) - Lithuanian community with a CoreScope instance and Telegram group.

### Netherlands

- [Dutch MeshCore](https://dutchmeshcore.nl/) - Dutch node directory and radio preset reference.
- [LocalMesh Nederland](https://www.localmesh.nl/) - Dutch emergency network with setup guides.
- [MeshCore Forum NL](https://forum.meshcore-net.nl/) - Dutch-language forum.
- [MeshCore Nederland](https://www.meshcore.nl/) - Dutch national site.
- [MeshWiki NL](https://meshwiki.nl/) - Collaborative Dutch documentation wiki.

### New Zealand

- [Meshed](https://meshed.kiwi/) - New Zealand community network.

### Norway

- [MeshWiki.no](https://meshwiki.no/) - Norwegian documentation hub and preset reference.

### Poland

- [LoRa MeshCore Polska](https://lorameshcore.pl/) - Nationwide Polish off-grid network on the EU/UK narrow preset.
- [MeshCore Podlasie](https://meshcore.podlasie.pl/) - Hobbyist network in the Podlasie region, with news, settings and a forum.
- [MeshCore Polska](https://meshcorepolska.org/) - Polish network coordination hub.
- [MeshGo](https://meshgo.pl/) - Polish community hub.

### Portugal

- [MeshCore Portugal](https://meshcore.pt/) - Portuguese community site.

### Romania

- [Brașov Mesh](https://brasovmesh.com/) - Brașov network on the EU/UK narrow preset.

### Slovakia

- [MeshCore Slovensko](https://mesh.om3kff.sk/) - Slovak national mesh with map and Discord.

### Spain

- [MeshCore Catalunya](https://docs.livemap-meshcorecat.com/) - Catalonia community with live map and documentation.
- [NomadMesh](https://nomadmesh.org/) - Alpujarra region community network.
- [RegionMesh España](https://www.regionmesh.com/es/) - Spanish-language community hub and guides.

### Sweden

- [Meshat.se](https://meshcore.meshat.se/) - Swedish network map and resources.

### Switzerland

- [MeshCore Switzerland](https://www.meshcore.ch/) - Swiss community site.

### Ukraine

- [MeshCore Ukraine](https://meshcore-ua.net/) - Volunteer-run public mesh for resilient communication across Ukraine.

### United Kingdom

- [IPNet](https://ipnt.uk/) - Ipswich hub with CoreScope dashboards and MQTT services.
- [LocalMesh UK](https://localmesh.co.uk/) - UK emergency network with city communities.
- [MeshCore Wales](https://meshcore.wales/) - Welsh regional settings and coordination.
- [MeshHub UK](https://meshhub.uk/) - National coordination platform.
- [NorthMesh](https://northmesh.co.uk/) - Northern England community network.
- [ScotMesh](https://scotmesh.mm7roq.compute.oarc.uk/) - Scottish community tools.

### United States

- [Austin Mesh](https://www.austinmesh.org/) - Austin, Texas community.
- [Bay Area MeshCore](https://bayareameshcore.org/) - San Francisco Bay Area network.
- [Chicagoland Mesh](https://chicagolandmesh.org/) - Chicago-area MeshCore, Meshtastic and Reticulum community.
- [Colorado MeshCore](https://meshcore.coloradomesh.org/) - Colorado community and guides.
- [CT Mesh](https://ctmesh.org/) - Connecticut mesh technologies user group.
- [Denver MeshCore](https://denvermc.com/) - Denver metro community.
- [Eastern US MeshCore](https://eastme.sh/) - Eastern states network.
- [Florida Mesh](https://areyoumeshingwith.us/) - Florida-wide network run by amateur radio operators.
- [Gulf Coast Mesh](https://gulfcoastmesh.org) - Louisiana and US Gulf Coast network.
- [Idaho Mesh](https://idahomesh.org) - Idaho network centred on the Treasure Valley.
- [Inland NW Mesh](https://inlandnwmesh.org/) - Spokane, Coeur d'Alene, the Palouse and Lewiston/Clarkston.
- [Lehigh Valley Mesh](https://lvmesh.com/) - Lehigh Valley and eastern Pennsylvania.
- [Madison Mesh](https://madmesh.net/) - Community-owned network in Madison, Wisconsin.
- [Mesh America](https://meshamerica.com/) - Guides, wiki and network design articles.
- [MeshCore TX](https://meshcoretx.net/) - Texas radio preset and repeater naming standard.
- [MeshTexas](https://meshtexas.net/) - Statewide Texas network with a shared MQTT broker.
- [Mountain West Mesh](https://mwmesh.com/) - Utah, Idaho and Wyoming network.
- [MSP Mesh](https://mspmesh.org/) - Minneapolis-Saint Paul and Greater Minnesota group.
- [Nebraska Mesh](https://www.nebraskamesh.net/) - Statewide Nebraska network.
- [New England Mesh](https://nhmesh.com/) - New England-wide community across CT, MA, NH and ME.
- [NodakMesh](https://nodakmesh.org/) - North Dakota community with wiki and guides.
- [NTX Mesh](https://ntxmesh.com/) - Dallas-Fort Worth and greater North Texas.
- [Pioneer Valley Mesh](https://pvmesh.org/) - Pioneer Valley of western Massachusetts.
- [Puget Mesh](https://pugetmesh.org/) - Puget Sound region off-grid communication networks.
- [RDUMesh](https://rdumesh.org/) - Raleigh, Durham and Chapel Hill network.
- [RegionMesh](https://www.regionmesh.com/) - National hub with regional guides.
- [Southern California MeshCore](https://socalmesh.org/) - Los Angeles area community with a public CoreScope instance.
- [Spokane Mesh](https://www.spokanemesh.net/) - Spokane regional network.
- [STMesh](https://www.stmesh.net/) - New York Southern Tier networks.
- [TennMesh](https://tennmesh.com/) - Tennessee network community.
- [Upstate Mesh](https://www.upst8me.sh/) - New York Capital District community.
- [West Coast Mesh](https://www.wcmesh.com/) - West Coast community hub and coordination.
- [WNY MeshCore](https://wnymeshcore.org/) - Western New York communication backbone.
