# Awesome MeshCore [![Awesome list badge](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome MeshCore resources. Pull requests welcome!

MeshCore is a multi-platform system for enabling secure text based
communications utilising LoRa radio hardware. It can be used for off-grid
communication, emergency response & disaster recovery, outdoor activities and IoT
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
- [Libraries and SDKs](#libraries-and-sdks)
- [Integrations and Bots](#integrations-and-bots)
- [Self-Hosted Dashboards](#self-hosted-dashboards)
- [Packet Analysis](#packet-analysis)
- [Utilities](#utilities)
- [Guides and Learning](#guides-and-learning)
- [Communities](#communities)
  - [Virtual](#virtual)
  - [Country / region sections](#country--region-websites)

Apps and firmware marked 🔒 are closed source.

---

## Official Resources

- [MeshCore.io](https://meshcore.io/) - The official homepage.
- [Documentation](https://docs.meshcore.io/) - Official docs.
- [Blog](https://blog.meshcore.io/) - Official announcements and releases.
- [MeshCore Web Flasher](https://flasher.meshcore.io/) - Official browser-based firmware flasher for supported devices.
- [MeshCore Companion Web App](https://app.meshcore.io/) 🔒 - Official web build of the companion app.
- [MeshCore Map](https://map.meshcore.io/) - Official network map.
- [The FAQ](https://github.com/meshcore-dev/MeshCore/blob/main/docs/faq.md) - Official answers on setup, roles and radio settings.
- [Firmware repository](https://github.com/meshcore-dev/MeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-dev/MeshCore?style=social) - MIT licensed firmware. ![GitHub last commit](https://img.shields.io/github/last-commit/meshcore-dev/MeshCore)
- [Current state of MeshCore encryption](https://github.com/meshcore-dev/MeshCore/issues/259) - Discussion thread on the project's encryption roadmap.

### Social Media

- [Discord](https://meshcore.gg) - Official server.
- [Reddit r/meshcore](https://www.reddit.com/r/meshcore/) - Official subreddit.
- [Facebook group](https://www.facebook.com/groups/meshcore)
- [Mastodon](https://mastodon.social/@meshcore)
- [X](https://x.com/mesh_core)
- [YouTube](https://www.youtube.com/@meshcore-official)

## Client

Grouped by platform. Apps marked 🔒 are closed source.

### Cross-Platform

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [Official app](https://files.liamcottle.net/MeshCore/) 🔒 | Proprietary companion app, also on Google Play and the App Store. | |
| [Meshcore Open](https://github.com/zjs81/meshcore-open) ![GitHub Repo stars](https://img.shields.io/github/stars/zjs81/meshcore-open?style=social) | Open-source Flutter client for mobile and desktop (Android, iOS, GNU/Linux, Windows, macOS). | ![GitHub last commit](https://img.shields.io/github/last-commit/zjs81/meshcore-open) |
| [MCO Advanced](https://github.com/HDDen/meshcore-open) ![GitHub Repo stars](https://img.shields.io/github/stars/HDDen/meshcore-open?style=social) | MeshCore Open fork with one-packet lossless image sending (MCOimg), built-in wardriving and text compression. | ![GitHub last commit](https://img.shields.io/github/last-commit/HDDen/meshcore-open) |
| [KIEKR](https://kiekr.app/) 🔒 | iOS and Android community toolbox app; can display incoming message scope, upload data to analysers, unlimited contacts. | |
| [Meshcore SAR](https://github.com/dz0ny/meshcore-sar) ![GitHub Repo stars](https://img.shields.io/github/stars/dz0ny/meshcore-sar?style=social) | Offline-first search-and-rescue app: messaging, voice, images, maps and live location context in one app. (AI code) | ![GitHub last commit](https://img.shields.io/github/last-commit/dz0ny/meshcore-sar) |
| [Nelos](https://nelos.app/) 🔒 | iOS/Android app for group messaging and tracking people, pets and belongings, with downloadable offline maps. | |
| [Offband MeshCore](https://github.com/OffbandMesh/meshcore-client) ![GitHub Repo stars](https://img.shields.io/github/stars/OffbandMesh/meshcore-client?style=social) | Cross-platform client with direct and channel chat. | ![GitHub last commit](https://img.shields.io/github/last-commit/OffbandMesh/meshcore-client) |
| [SigurdOS Client](https://github.com/hermes-gadget/SigurdOS-client) ![GitHub Repo stars](https://img.shields.io/github/stars/hermes-gadget/SigurdOS-client?style=social) | Companion app for GNU/Linux, Android, iOS, Windows, macOS, forked from Meshcore Open for "SigurdOS T-Deck" firmware. | ![GitHub last commit](https://img.shields.io/github/last-commit/hermes-gadget/SigurdOS-client) |
| [MeshCore TEAM](https://github.com/tmacinc/MeshCore-TEAM) ![GitHub Repo stars](https://img.shields.io/github/stars/tmacinc/MeshCore-TEAM?style=social) | Source of the cross-platform MeshCore TEAM companion app: team-oriented location tracking, messaging, contacts, channels and maps on stock firmware. | ![GitHub last commit](https://img.shields.io/github/last-commit/tmacinc/MeshCore-TEAM) |

### Android

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [meshcore-mobile-app](https://github.com/thatSFguy/meshcore-mobile-app) ![GitHub Repo stars](https://img.shields.io/github/stars/thatSFguy/meshcore-mobile-app?style=social) | Hardened Android client, no Google Play Services required. | ![GitHub last commit](https://img.shields.io/github/last-commit/thatSFguy/meshcore-mobile-app) |
| [MeshCore-TEAM](https://play.google.com/store/apps/details?id=com.meshcore.team) 🔒 | Android client focused on group operations (Play Store build of [MeshCore TEAM](https://github.com/tmacinc/MeshCore-TEAM)). | |
| [Tactical Emergency Area Messaging](https://github.com/tmacinc/meshcore-team-alpha) ![GitHub Repo stars](https://img.shields.io/github/stars/tmacinc/meshcore-team-alpha?style=social) | Android application for position tracking and messaging. | ![GitHub last commit](https://img.shields.io/github/last-commit/tmacinc/meshcore-team-alpha) |
| [Meshcore-Wardrive-Android](https://github.com/mintylinux/Meshcore-Wardrive-Android) ![GitHub Repo stars](https://img.shields.io/github/stars/mintylinux/Meshcore-Wardrive-Android?style=social) | Flutter wardriving and mapping app. | ![GitHub last commit](https://img.shields.io/github/last-commit/mintylinux/Meshcore-Wardrive-Android) |
| [meshGO!](https://play.google.com/store/apps/details?id=com.meshcore.meshgo) 🔒 | Android off-grid messaging client. | |
| [MeshMapper](https://play.google.com/store/apps/details?id=net.meshmapper.app) 🔒 | Android coverage mapping and wardriving app. | |
| [meshtrax](https://github.com/venamartin/meshtrax) ![GitHub Repo stars](https://img.shields.io/github/stars/venamartin/meshtrax?style=social) | Flutter Android client with mapping and messaging. | ![GitHub last commit](https://img.shields.io/github/last-commit/venamartin/meshtrax) |
| [Yours](https://github.com/STCisGOOD/yours-x-lunarcore) ![GitHub Repo stars](https://img.shields.io/github/stars/STCisGOOD/yours-x-lunarcore?style=social) | Android encrypted P2P messaging client for LunarCore firmware, with onion-routing experiments. | ![GitHub last commit](https://img.shields.io/github/last-commit/STCisGOOD/yours-x-lunarcore) |

### iOS and Apple

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [MeshCore One](https://github.com/Avi0n/MeshCoreOne) ![GitHub Repo stars](https://img.shields.io/github/stars/Avi0n/MeshCoreOne?style=social) | Native Swift client for iOS, iPadOS and macOS. (AI code) | ![GitHub last commit](https://img.shields.io/github/last-commit/Avi0n/MeshCoreOne) |
| [PommeCore](https://github.com/mbedworth/PommeCore) ![GitHub Repo stars](https://img.shields.io/github/stars/mbedworth/PommeCore?style=social) | SwiftUI companion app for Apple platforms. | ![GitHub last commit](https://img.shields.io/github/last-commit/mbedworth/PommeCore) |

### Desktop

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [mesh-client](https://github.com/Colorado-Mesh/mesh-client) ![GitHub Repo stars](https://img.shields.io/github/stars/Colorado-Mesh/mesh-client?style=social) | Electron desktop client for MeshCore, Meshtastic and Reticulum. | ![GitHub last commit](https://img.shields.io/github/last-commit/Colorado-Mesh/mesh-client) |
| [MeshApp](https://github.com/smikme/meshapp) ![GitHub Repo stars](https://img.shields.io/github/stars/smikme/meshapp?style=social) | Desktop client for MeshCore and Meshtastic with telemetry views. | ![GitHub last commit](https://img.shields.io/github/last-commit/smikme/meshapp) |
| [MeshCore gui](https://github.com/pe1hvh/meshcore-gui) ![GitHub Repo stars](https://img.shields.io/github/stars/pe1hvh/meshcore-gui?style=social) | Native desktop client over BLE, no firmware changes required. | ![GitHub last commit](https://img.shields.io/github/last-commit/pe1hvh/meshcore-gui) |
| [MeshCore Insights](https://github.com/BomBefok/MeshcoreInsights) ![GitHub Repo stars](https://img.shields.io/github/stars/BomBefok/MeshcoreInsights?style=social) | Desktop dashboard with live maps, telemetry analysis and remote node management. | ![GitHub last commit](https://img.shields.io/github/last-commit/BomBefok/MeshcoreInsights) |
| [meshcore-bin (AUR)](https://aur.archlinux.org/packages/meshcore-bin) 🔒 | Arch Linux package of the official app. | |
| [MeshCoreQt](https://github.com/zhrkvl/MeshCoreQt) ![GitHub Repo stars](https://img.shields.io/github/stars/zhrkvl/MeshCoreQt?style=social) | Qt desktop client. | ![GitHub last commit](https://img.shields.io/github/last-commit/zhrkvl/MeshCoreQt) |
| [meshy](https://codeberg.org/sesivany/meshy) | GTK4/libadwaita client for Linux and macOS, aiming for the best Linux experience. | |
| [PyMeshCoreGUI](https://github.com/bliksemlabs/PyMeshCoreGUI) ![GitHub Repo stars](https://img.shields.io/github/stars/bliksemlabs/PyMeshCoreGUI?style=social) | Qt6 and Python desktop client. | ![GitHub last commit](https://img.shields.io/github/last-commit/bliksemlabs/PyMeshCoreGUI) |
| [QMeshcoreApp](https://github.com/FelixvdDonk/QMeshcoreApp) ![GitHub Repo stars](https://img.shields.io/github/stars/FelixvdDonk/QMeshcoreApp?style=social) | Qt6/QML desktop companion with BLE/serial, map and RX log. | ![GitHub last commit](https://img.shields.io/github/last-commit/FelixvdDonk/QMeshcoreApp) |

### Web

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [Official web app](https://app.meshcore.io/) 🔒 | Browser build of the official companion app. | |
| [meshcore-web (aXistem)](https://github.com/aXistem-dev/meshcore-web) ![GitHub Repo stars](https://img.shields.io/github/stars/aXistem-dev/meshcore-web?style=social) | Docker-ready browser build of the companion app over BLE or USB; image `ghcr.io/axistem-dev/meshcore-web`. | ![GitHub last commit](https://img.shields.io/github/last-commit/aXistem-dev/meshcore-web) |
| [meshcore-web (Vue)](https://github.com/liamcottle/meshcore-web) ![GitHub Repo stars](https://img.shields.io/github/stars/liamcottle/meshcore-web?style=social) | Early Vue web client, superseded by the official app. | ![GitHub last commit](https://img.shields.io/github/last-commit/liamcottle/meshcore-web) |
| [meshcore-webui](https://github.com/adradr/meshcore-webui) ![GitHub Repo stars](https://img.shields.io/github/stars/adradr/meshcore-webui?style=social) | Web UI for managing devices and chatting on the mesh. | ![GitHub last commit](https://img.shields.io/github/last-commit/adradr/meshcore-webui) |
| [MC-WebUI](https://github.com/MarekWo/mc-webui) ![GitHub Repo stars](https://img.shields.io/github/stars/MarekWo/mc-webui?style=social) | WebUI for meshcore-cli. (AI code) | ![GitHub last commit](https://img.shields.io/github/last-commit/MarekWo/mc-webui) |
| [MeshCorium](https://github.com/PEG4TRON/MeshCorium) ![GitHub Repo stars](https://img.shields.io/github/stars/PEG4TRON/MeshCorium?style=social) | Self-hosted client with a local web interface and hybrid contact system. | ![GitHub last commit](https://img.shields.io/github/last-commit/PEG4TRON/MeshCorium) |
| [Mycelium](https://github.com/WattleFoxxo/Mycelium) ![GitHub Repo stars](https://img.shields.io/github/stars/WattleFoxxo/Mycelium?style=social) | Browser client for messaging over serial or BLE. | ![GitHub last commit](https://img.shields.io/github/last-commit/WattleFoxxo/Mycelium) |

### Terminal

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [MeshChaTUI](https://github.com/g-d-j-evans/MeschaTUI) ![GitHub Repo stars](https://img.shields.io/github/stars/g-d-j-evans/MeschaTUI?style=social) | Textual terminal client for Linux with delivery confirmation over serial or BLE. | ![GitHub last commit](https://img.shields.io/github/last-commit/g-d-j-evans/MeschaTUI) |
| [MeshTerm](https://meshterm.net/) 🔒 | Cross-platform TUI client over USB, BLE or TCP with maps, traceroute and message-path views. | |
| [meshtui](https://github.com/ekollof/meshtui) ![GitHub Repo stars](https://img.shields.io/github/stars/ekollof/meshtui?style=social) | Textual terminal client with delivery tracking and device management. | ![GitHub last commit](https://img.shields.io/github/last-commit/ekollof/meshtui) |
| [QTC](https://github.com/initsixdev/QTC) ![GitHub Repo stars](https://img.shields.io/github/stars/initsixdev/QTC?style=social) | Old-school terminal client for Linux and macOS. | ![GitHub last commit](https://img.shields.io/github/last-commit/initsixdev/QTC) |
| [Remote Terminal for MeshCore](https://github.com/MichTronics/Remote-Terminal-for-MeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/MichTronics/Remote-Terminal-for-MeshCore?style=social) | Remote terminal for repeaters with packet capture and MQTT. | ![GitHub last commit](https://img.shields.io/github/last-commit/MichTronics/Remote-Terminal-for-MeshCore) |
| [tui-meshcore](https://github.com/guax/tui-meshcore) ![GitHub Repo stars](https://img.shields.io/github/stars/guax/tui-meshcore?style=social) | Terminal chat client with persistent history and regional presets. | ![GitHub last commit](https://img.shields.io/github/last-commit/guax/tui-meshcore) |

### Other Platforms

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [MeshCore64](https://github.com/swannman/meshcore64) ![GitHub Repo stars](https://img.shields.io/github/stars/swannman/meshcore64?style=social) | Commodore 64 chat client over a SwiftLink-compatible serial cartridge. | ![GitHub last commit](https://img.shields.io/github/last-commit/swannman/meshcore64) |
| [PicoMeshCore](https://github.com/Vigoleis912/PicoMeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/Vigoleis912/PicoMeshCore?style=social) | MMBasic companion client for the Raspberry Pi Pico (PicoMite) over UART. | ![GitHub last commit](https://img.shields.io/github/last-commit/Vigoleis912/PicoMeshCore) |
| [Roadstr](https://github.com/jooray/roadstr) ![GitHub Repo stars](https://img.shields.io/github/stars/jooray/roadstr?style=social) | Decentralized road-event reporting over signed Nostr events with MeshCore as transport — "Waze without the centralized tracking." | ![GitHub last commit](https://img.shields.io/github/last-commit/jooray/roadstr) |
| [Sestriere](https://github.com/atomozero/Sestriere) ![GitHub Repo stars](https://img.shields.io/github/stars/atomozero/Sestriere?style=social) | Native Haiku OS client with maps, packet analysis and repeater administration. (AI code) | ![GitHub last commit](https://img.shields.io/github/last-commit/atomozero/Sestriere) |

## Libraries and SDKs

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [meshcore_py](https://github.com/meshcore-dev/meshcore_py) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-dev/meshcore_py?style=social) | Official Python bindings over serial, BLE and TCP. | ![GitHub last commit](https://img.shields.io/github/last-commit/meshcore-dev/meshcore_py) |
| [meshcore.js](https://github.com/meshcore-dev/meshcore.js) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-dev/meshcore.js?style=social) | Official JavaScript companion radio library. | ![GitHub last commit](https://img.shields.io/github/last-commit/meshcore-dev/meshcore.js) |
| [meshcore-cli](https://github.com/meshcore-dev/meshcore-cli) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-dev/meshcore-cli?style=social) | Official command line interface for nodes. | ![GitHub last commit](https://img.shields.io/github/last-commit/meshcore-dev/meshcore-cli) |
| [meshcore_client](https://github.com/dz0ny/meshcore_client) ![GitHub Repo stars](https://img.shields.io/github/stars/dz0ny/meshcore_client?style=social) | Flutter/Dart implementation of the BLE companion protocol. | ![GitHub last commit](https://img.shields.io/github/last-commit/dz0ny/meshcore_client) |
| [meshcore_upy](https://github.com/fdlamotte/meshcore_upy) ![GitHub Repo stars](https://img.shields.io/github/stars/fdlamotte/meshcore_upy?style=social) | MicroPython bindings. | ![GitHub last commit](https://img.shields.io/github/last-commit/fdlamotte/meshcore_upy) |
| [meshcore-go (meshcore-cz)](https://github.com/meshcore-cz/meshcore-go) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-cz/meshcore-go?style=social) | Transport-independent Go SDK over serial, BLE and TCP. | ![GitHub last commit](https://img.shields.io/github/last-commit/meshcore-cz/meshcore-go) |
| [meshcore-go](https://github.com/meshcore-go/meshcore-go) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-go/meshcore-go?style=social) | Pure Go protocol implementation. | ![GitHub last commit](https://img.shields.io/github/last-commit/meshcore-go/meshcore-go) |
| [meshcore-packets-java](https://github.com/msmuenchen/meshcore-packets-java) ![GitHub Repo stars](https://img.shields.io/github/stars/msmuenchen/meshcore-packets-java?style=social) | Java packet encoder and decoder. | ![GitHub last commit](https://img.shields.io/github/last-commit/msmuenchen/meshcore-packets-java) |
| [meshcore-pi](https://github.com/brianwiddas/meshcore-pi) ![GitHub Repo stars](https://img.shields.io/github/stars/brianwiddas/meshcore-pi?style=social) | Python protocol implementation for Raspberry Pi and other Linux hosts. | ![GitHub last commit](https://img.shields.io/github/last-commit/brianwiddas/meshcore-pi) |
| [meshcore-rs](https://github.com/andrewdavidmackenzie/meshcore-rs) ![GitHub Repo stars](https://img.shields.io/github/stars/andrewdavidmackenzie/meshcore-rs?style=social) | Rust port of the Python library. | ![GitHub last commit](https://img.shields.io/github/last-commit/andrewdavidmackenzie/meshcore-rs) |
| [meshcore-ts](https://github.com/dpup/meshcore-ts) ![GitHub Repo stars](https://img.shields.io/github/stars/dpup/meshcore-ts?style=social) | Typed TypeScript client over TCP/WiFi and USB serial. | ![GitHub last commit](https://img.shields.io/github/last-commit/dpup/meshcore-ts) |
| [MeshCoreCompanion (meshcore_c)](https://github.com/SH3D/meshcore_c) ![GitHub Repo stars](https://img.shields.io/github/stars/SH3D/meshcore_c?style=social) | Portable C99 companion protocol library with an Arduino C++ wrapper (ESP32, nRF52, STM32, desktop). | ![GitHub last commit](https://img.shields.io/github/last-commit/SH3D/meshcore_c) |
| [MeshCoreKmp](https://github.com/Wavesonics/MeshCoreKmp) ![GitHub Repo stars](https://img.shields.io/github/stars/Wavesonics/MeshCoreKmp?style=social) | Kotlin Multiplatform library for BLE companion nodes. | ![GitHub last commit](https://img.shields.io/github/last-commit/Wavesonics/MeshCoreKmp) |
| [meshpkt](https://github.com/meshcore-cz/meshpkt) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-cz/meshpkt?style=social) | Pure Go packet codec with identity cryptography and TypeScript WebAssembly bindings. | ![GitHub last commit](https://img.shields.io/github/last-commit/meshcore-cz/meshpkt) |
| [openHop Core](https://github.com/openhop-dev/openhop_core) ![GitHub Repo stars](https://img.shields.io/github/stars/openhop-dev/openhop_core?style=social) | Python reimplementation of the protocol and routing stack, with direct SX1262 support. | ![GitHub last commit](https://img.shields.io/github/last-commit/openhop-dev/openhop_core) |

## Integrations and Bots

| Project Name | Connection | Description | Last Updated |
| :--- | :---: | :--- | :---: |
| [meshcore-ha](https://github.com/meshcore-dev/meshcore-ha) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-dev/meshcore-ha?style=social) | — | Official Home Assistant integration, installable via HACS. | ![GitHub last commit](https://img.shields.io/github/last-commit/meshcore-dev/meshcore-ha) |
| [BinktermPHP](https://github.com/awehttam/binkterm-php) ![GitHub Repo stars](https://img.shields.io/github/stars/awehttam/binkterm-php?style=social) | — | Full-stack Bulletin Board System with a MeshCore gateway, web and telnet access, and FidoNet. | ![GitHub last commit](https://img.shields.io/github/last-commit/awehttam/binkterm-php) |
| [Cyclenerd MeshCore Bot](https://github.com/Cyclenerd/meshcore-bot) ![GitHub Repo stars](https://img.shields.io/github/stars/Cyclenerd/meshcore-bot?style=social) | Serial | Node.js command bot with scheduled repeater status collection. | ![GitHub last commit](https://img.shields.io/github/last-commit/Cyclenerd/meshcore-bot) |
| [Domoticz MeshCore Plugin](https://github.com/galadril/Domoticz-MeshCore-Plugin) ![GitHub Repo stars](https://img.shields.io/github/stars/galadril/Domoticz-MeshCore-Plugin?style=social) | — | Exposes nodes, telemetry and messaging as native Domoticz devices. | ![GitHub last commit](https://img.shields.io/github/last-commit/galadril/Domoticz-MeshCore-Plugin) |
| [ESPHome MeshCore](https://github.com/netmilk/esphome-meshcore) ![GitHub Repo stars](https://img.shields.io/github/stars/netmilk/esphome-meshcore?style=social) | — | ESPHome component turning XIAO nRF52840 boards into managed MeshCore sensor nodes; control switches, sensors, fans and lights over LoRa mesh from the Companion app. | ![GitHub last commit](https://img.shields.io/github/last-commit/netmilk/esphome-meshcore) |
| [HopLink](https://github.com/A13xB0/hoplink) ![GitHub Repo stars](https://img.shields.io/github/stars/A13xB0/hoplink?style=social) | TCP/IP | Bridge between MeshCore, Meshtastic and Discord. | ![GitHub last commit](https://img.shields.io/github/last-commit/A13xB0/hoplink) |
| [map.meshcore.io uploader](https://github.com/recrof/map.meshcore.io-uploader) ![GitHub Repo stars](https://img.shields.io/github/stars/recrof/map.meshcore.io-uploader?style=social) | Serial | Uploads every repeater and room server a companion hears to the public map. | ![GitHub last commit](https://img.shields.io/github/last-commit/recrof/map.meshcore.io-uploader) |
| [Mesh-Citadel BBS](https://github.com/taedryn/mesh-citadel) ![GitHub Repo stars](https://img.shields.io/github/stars/taedryn/mesh-citadel?style=social) | — | Citadel-style BBS reachable over the mesh, inspired by 80s Citadel BBSes. | ![GitHub last commit](https://img.shields.io/github/last-commit/taedryn/mesh-citadel) |
| [MeshCore BBS](https://github.com/carsten-walther/MeshCore-BBS) ![GitHub Repo stars](https://img.shields.io/github/stars/carsten-walther/MeshCore-BBS?style=social) | — | Store-and-forward bulletin board running on a companion radio. | ![GitHub last commit](https://img.shields.io/github/last-commit/carsten-walther/MeshCore-BBS) |
| [MeshCore Discord Bridge](https://github.com/Hude06/MeshCoreDiscordBridge) ![GitHub Repo stars](https://img.shields.io/github/stars/Hude06/MeshCoreDiscordBridge?style=social) | Serial | Bidirectional Discord bridge with multi-channel routing and flood protection. | ![GitHub last commit](https://img.shields.io/github/last-commit/Hude06/MeshCoreDiscordBridge) |
| [MeshCore Email Gateway](https://github.com/MGJ520/MeshCore-Email-Gateway) ![GitHub Repo stars](https://img.shields.io/github/stars/MGJ520/MeshCore-Email-Gateway?style=social) | — | Bidirectional SMTP/IMAP gateway with a management API and web interface. | ![GitHub last commit](https://img.shields.io/github/last-commit/MGJ520/MeshCore-Email-Gateway) |
| [MeshCore SAME EAS Alerter](https://github.com/Mambo430/MeshCore-SAME-EAS-Alerter) ![GitHub Repo stars](https://img.shields.io/github/stars/Mambo430/MeshCore-SAME-EAS-Alerter?style=social) | — | Forwards SAME emergency alert broadcasts onto the mesh. | ![GitHub last commit](https://img.shields.io/github/last-commit/Mambo430/MeshCore-SAME-EAS-Alerter) |
| [MeshCore UI for Home Assistant](https://github.com/Ratty7198/MeshCore-HA-UI) ![GitHub Repo stars](https://img.shields.io/github/stars/Ratty7198/MeshCore-HA-UI?style=social) | — | HACS sidebar dashboard on top of meshcore-ha with chat, contacts and maps. | ![GitHub last commit](https://img.shields.io/github/last-commit/Ratty7198/MeshCore-HA-UI) |
| [meshcore-bot](https://github.com/agessaman/meshcore-bot) ![GitHub Repo stars](https://img.shields.io/github/stars/agessaman/meshcore-bot?style=social) | Serial, BLE or TCP/IP | Python command bot with Discord and Telegram bridging plus a web viewer. | ![GitHub last commit](https://img.shields.io/github/last-commit/agessaman/meshcore-bot) |
| [meshcore-bot (Go)](https://github.com/meshcore-go/meshcore-bot) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-go/meshcore-bot?style=social) | — | Lightweight command bot in Go. | ![GitHub last commit](https://img.shields.io/github/last-commit/meshcore-go/meshcore-bot) |
| [meshcore-discord-relay](https://github.com/yellowcooln/meshcore-discord-relay) ![GitHub Repo stars](https://img.shields.io/github/stars/yellowcooln/meshcore-discord-relay?style=social) | MQTT | Relays MQTT traffic into Discord channels. | ![GitHub last commit](https://img.shields.io/github/last-commit/yellowcooln/meshcore-discord-relay) |
| [meshcore-mcp](https://github.com/dpup/meshcore-mcp) ![GitHub Repo stars](https://img.shields.io/github/stars/dpup/meshcore-mcp?style=social) | — | Model Context Protocol server exposing a node to AI agents. | ![GitHub last commit](https://img.shields.io/github/last-commit/dpup/meshcore-mcp) |
| [meshcore-mqtt](https://github.com/ipnet-mesh/meshcore-mqtt) ![GitHub Repo stars](https://img.shields.io/github/stars/ipnet-mesh/meshcore-mqtt?style=social) | Serial, BLE or TCP | MQTT bridge with TLS support. | ![GitHub last commit](https://img.shields.io/github/last-commit/ipnet-mesh/meshcore-mqtt) |
| [Meshcore-Repeater-MQTT-Gateway](https://github.com/jmead/Meshcore-Repeater-MQTT-Gateway) ![GitHub Repo stars](https://img.shields.io/github/stars/jmead/Meshcore-Repeater-MQTT-Gateway?style=social) | MQTT | Gateway firmware bridging repeaters to MQTT. | ![GitHub last commit](https://img.shields.io/github/last-commit/jmead/Meshcore-Repeater-MQTT-Gateway) |
| [meshcoretomqtt](https://github.com/Cisien/meshcoretomqtt) ![GitHub Repo stars](https://img.shields.io/github/stars/Cisien/meshcoretomqtt?style=social) | MQTT | Publishes debug and packet capture output to MQTT. | ![GitHub last commit](https://img.shields.io/github/last-commit/Cisien/meshcoretomqtt) |
| [Meshpoint](https://github.com/KMX415/meshpoint) ![GitHub Repo stars](https://img.shields.io/github/stars/KMX415/meshpoint?style=social) | — | Raspberry Pi base station using an SX1302/SX1303 LoRa concentrator. | ![GitHub last commit](https://img.shields.io/github/last-commit/KMX415/meshpoint) |
| [MeshRes](https://github.com/bryantkelley/MeshRes) ![GitHub Repo stars](https://img.shields.io/github/stars/bryantkelley/MeshRes?style=social) | — | Streams mesh messages into the Resonite social VR platform. | ![GitHub last commit](https://img.shields.io/github/last-commit/bryantkelley/MeshRes) |
| [openHop Repeater](https://github.com/openhop-dev/openhop_repeater) ![GitHub Repo stars](https://img.shields.io/github/stars/openhop-dev/openhop_repeater?style=social) | — | Python repeater daemon for Pi-class and embedded Linux hardware, built on openHop Core. | ![GitHub last commit](https://img.shields.io/github/last-commit/openhop-dev/openhop_repeater) |
| [PokeMesh](https://github.com/IdreesInc/PokeMesh) ![GitHub Repo stars](https://img.shields.io/github/stars/IdreesInc/PokeMesh?style=social) | Serial | Collaborative Pokémon FireRed played through channel commands, turning the game into a text adventure over MeshCore. | ![GitHub last commit](https://img.shields.io/github/last-commit/IdreesInc/PokeMesh) |
| [Spectra](https://forge.hackers.town/Wrewdison/Spectra) | — | Rust bridge from MeshCore or Meshtastic radios to the Veilid DHT. | |
| [Supply Drop BBS](https://supplydrop.meshamerica.com/) 🔒 | — | Rust BBS for Raspberry Pi with MeshCore and Meshtastic bridges and a plugin system for other transports. | |

## Self-Hosted Dashboards

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [CoreScope (Kpa-clawbot)](https://github.com/Kpa-clawbot/CoreScope) ![GitHub Repo stars](https://img.shields.io/github/stars/Kpa-clawbot/CoreScope?style=social) | Packet analyzer with MQTT ingest, maps, channel chat and per-node analytics. | ![GitHub last commit](https://img.shields.io/github/last-commit/Kpa-clawbot/CoreScope) |
| [LiteScope](https://github.com/RikoDEV/litescope) ![GitHub Repo stars](https://img.shields.io/github/stars/RikoDEV/litescope?style=social) | Lightweight MQTT dashboard for node and telemetry monitoring. | ![GitHub last commit](https://img.shields.io/github/last-commit/RikoDEV/litescope) |
| [mc-webui](https://github.com/MarekWo/mc-webui) ![GitHub Repo stars](https://img.shields.io/github/stars/MarekWo/mc-webui?style=social) | Flask web client with SQLite storage and Docker deployment. | ![GitHub last commit](https://img.shields.io/github/last-commit/MarekWo/mc-webui) |
| [MeshCore Beacon](https://github.com/MeshCore-Beacon/beacon-server) ![GitHub Repo stars](https://img.shields.io/github/stars/MeshCore-Beacon/beacon-server?style=social) | Go collector with PostgreSQL storage, WebSocket streaming and a React frontend. | ![GitHub last commit](https://img.shields.io/github/last-commit/MeshCore-Beacon/beacon-server) |
| [MeshCore MQTT Live Map](https://github.com/yellowcooln/meshcore-mqtt-live-map) ![GitHub Repo stars](https://img.shields.io/github/stars/yellowcooln/meshcore-mqtt-live-map?style=social) | Real-time traffic map with coverage, heat and line-of-sight views. | ![GitHub last commit](https://img.shields.io/github/last-commit/yellowcooln/meshcore-mqtt-live-map) |
| [meshcore-hub](https://github.com/ipnet-mesh/meshcore-hub) ![GitHub Repo stars](https://img.shields.io/github/stars/ipnet-mesh/meshcore-hub?style=social) | Collector, REST API and dashboard backed by PostgreSQL. (AI code) | ![GitHub last commit](https://img.shields.io/github/last-commit/ipnet-mesh/meshcore-hub) |
| [MeshExplorer](https://github.com/ajvpot/meshexplorer) ![GitHub Repo stars](https://img.shields.io/github/stars/ajvpot/meshexplorer?style=social) | Real-time map, chat client and packet analysis. | ![GitHub last commit](https://img.shields.io/github/last-commit/ajvpot/meshexplorer) |
| [MeshMonitor](https://meshmonitor.org/) ([GitHub repository](https://github.com/Yeraze/meshmonitor)) ![GitHub Repo stars](https://img.shields.io/github/stars/Yeraze/meshmonitor?style=social) | Self-hosted multi-protocol dashboard (MeshCore + Meshtastic) with maps, telemetry and automation. | ![GitHub last commit](https://img.shields.io/github/last-commit/Yeraze/meshmonitor) |
| [OverMesh](https://github.com/Slofi/overmesh) ![GitHub Repo stars](https://img.shields.io/github/stars/Slofi/overmesh?style=social) | Self-hosted dashboard for MeshCore and Meshtastic. | ![GitHub last commit](https://img.shields.io/github/last-commit/Slofi/overmesh) |
| [PotatoMesh](https://github.com/l5yth/potato-mesh) ![GitHub Repo stars](https://img.shields.io/github/stars/l5yth/potato-mesh?style=social) | Federated dashboard for local communities with remote ingestors and a public API. | ![GitHub last commit](https://img.shields.io/github/last-commit/l5yth/potato-mesh) |
| [pyMC Console](https://github.com/Treehouse-00/pymc_console-dist) ![GitHub Repo stars](https://img.shields.io/github/stars/Treehouse-00/pymc_console-dist?style=social) | Real-time web dashboard for openHop Repeater with RF statistics and terrain mapping. | ![GitHub last commit](https://img.shields.io/github/last-commit/Treehouse-00/pymc_console-dist) |
| [Remote Terminal for MeshCore (jkingsman)](https://github.com/jkingsman/Remote-Terminal-for-MeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/jkingsman/Remote-Terminal-for-MeshCore?style=social) | Power-user terminal with server-side packet capture, bots and MQTT integrations. | ![GitHub last commit](https://img.shields.io/github/last-commit/jkingsman/Remote-Terminal-for-MeshCore) |
| [UK Mesh](https://www.ukmesh.com/) ([GitHub repository](https://github.com/gadgethd/ukmesh)) ![GitHub Repo stars](https://img.shields.io/github/stars/gadgethd/ukmesh?style=social) | Real-time analytics platform with observer ingestion, coverage and packet views. | ![GitHub last commit](https://img.shields.io/github/last-commit/gadgethd/ukmesh) |

## Packet Analysis

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [CoreScope (OKI-Mesh)](https://github.com/OKI-Mesh/CoreScope) ![GitHub Repo stars](https://img.shields.io/github/stars/OKI-Mesh/CoreScope?style=social) | Live packet visualisation with replay and channel decryption. | ![GitHub last commit](https://img.shields.io/github/last-commit/OKI-Mesh/CoreScope) |
| [Lora Wideband Decoder](https://github.com/persistentcache/Lora-Wideband-Decoder) ![GitHub Repo stars](https://img.shields.io/github/stars/persistentcache/Lora-Wideband-Decoder?style=social) | SoapySDR wideband intercept receiver for LoRa traffic. | ![GitHub last commit](https://img.shields.io/github/last-commit/persistentcache/Lora-Wideband-Decoder) |
| [MCSim](https://github.com/Brent-A/mcsim) ![GitHub Repo stars](https://img.shields.io/github/stars/Brent-A/mcsim?style=social) | Deterministic simulation framework for firmware testing. | ![GitHub last commit](https://img.shields.io/github/last-commit/Brent-A/mcsim) |
| [MeshCore Packet Tool](https://github.com/meshcore-cz/meshcore-packet-tool) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-cz/meshcore-packet-tool?style=social) | Browser workbench for inspecting, decoding and crafting packets. | ![GitHub last commit](https://img.shields.io/github/last-commit/meshcore-cz/meshcore-packet-tool) |
| [MeshCore Signal Tester](https://github.com/kybl/meshcore-signal-tester) ![GitHub Repo stars](https://img.shields.io/github/stars/kybl/meshcore-signal-tester?style=social) | Real-time signal tester for companions and repeaters, with per-repeater SNR/RSSI charts and a 3D signal map. [Web](https://meshcore.kyblsoft.cz/signal-tester) + Android app. | ![GitHub last commit](https://img.shields.io/github/last-commit/kybl/meshcore-signal-tester) |
| [meshcore_sim](https://github.com/matthewdgreen/meshcore_sim) ![GitHub Repo stars](https://img.shields.io/github/stars/matthewdgreen/meshcore_sim?style=social) | Discrete-event simulator running real firmware routing logic. | ![GitHub last commit](https://img.shields.io/github/last-commit/matthewdgreen/meshcore_sim) |
| [meshcore-decoder-py](https://github.com/chrisdavis2110/meshcore-decoder-py) ![GitHub Repo stars](https://img.shields.io/github/stars/chrisdavis2110/meshcore-decoder-py?style=social) | Python packet decoder. | ![GitHub last commit](https://img.shields.io/github/last-commit/chrisdavis2110/meshcore-decoder-py) |
| [meshcore-decoder](https://github.com/michaelhart/meshcore-decoder) ![GitHub Repo stars](https://img.shields.io/github/stars/michaelhart/meshcore-decoder?style=social) | TypeScript library for decoding MeshCore packets with full cryptographic support. | ![GitHub last commit](https://img.shields.io/github/last-commit/michaelhart/meshcore-decoder) |
| [meshcore-packet-capture](https://github.com/agessaman/meshcore-packet-capture) ![GitHub Repo stars](https://img.shields.io/github/stars/agessaman/meshcore-packet-capture?style=social) | Captures packets from a companion radio and publishes to MQTT. | ![GitHub last commit](https://img.shields.io/github/last-commit/agessaman/meshcore-packet-capture) |
| [meshcore-packet-knife](https://github.com/jkingsman/meshcore-packet-knife) ![GitHub Repo stars](https://img.shields.io/github/stars/jkingsman/meshcore-packet-knife?style=social) | Packet inspection and WebGPU hashtag channel key bruteforcing. | ![GitHub last commit](https://img.shields.io/github/last-commit/jkingsman/meshcore-packet-knife) |
| [meshcore-sim](https://github.com/dpup/meshcore-sim) ![GitHub Repo stars](https://img.shields.io/github/stars/dpup/meshcore-sim?style=social) | Deterministic network simulator for testing without radios. | ![GitHub last commit](https://img.shields.io/github/last-commit/dpup/meshcore-sim) |
| [MeshCute](https://github.com/MadScientistCH/meshcute) ![GitHub Repo stars](https://img.shields.io/github/stars/MadScientistCH/meshcute?style=social) | Portable BLE, Wi-Fi and receive-only LoRa scanner for the M5Stack Cardputer Adv; universal toolbox for MeshCore/Meshtastic meetings. | ![GitHub last commit](https://img.shields.io/github/last-commit/MadScientistCH/meshcute) |
| [MeshCore Wireshark Dissector](https://github.com/aaronb/wireshark-meshcore) ![GitHub Repo stars](https://img.shields.io/github/stars/aaronb/wireshark-meshcore?style=social) | Wireshark protocol dissector and pcapng converter. | ![GitHub last commit](https://img.shields.io/github/last-commit/aaronb/wireshark-meshcore) |
| [YAMPA](https://github.com/guax/YAMPA) ![GitHub Repo stars](https://img.shields.io/github/stars/guax/YAMPA?style=social) | Yet another MeshCore packet analyser. | ![GitHub last commit](https://img.shields.io/github/last-commit/guax/YAMPA) |

## Utilities

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [Map Tiles Downloader](https://github.com/tekk/map-tiles-downloader) ![GitHub Repo stars](https://img.shields.io/github/stars/tekk/map-tiles-downloader?style=social) | Terminal utility for downloading offline OpenStreetMap tiles for mesh apps. | ![GitHub last commit](https://img.shields.io/github/last-commit/tekk/map-tiles-downloader) |
| [Mesh Utility](https://mesh-utility.org/) 🔒 | Progressive Web App for mapping MeshCore LoRa coverage with optional cloud ingestion. | |
| [MeshCore Geo Prune](https://static.pixelentry.de/meshcore/geo-prune/) 🔒 | Browser tool that cleans the contact list with a geofence. | |
| [MeshCore Proxy](https://github.com/rgregg/meshcore-proxy) ![GitHub Repo stars](https://img.shields.io/github/stars/rgregg/meshcore-proxy?style=social) | TCP proxy exposing a locally connected companion radio to remote clients. | ![GitHub last commit](https://img.shields.io/github/last-commit/rgregg/meshcore-proxy) |
| [MeshCore Regions catalog](https://github.com/marcelverdult/meshcore-regions) ![GitHub Repo stars](https://img.shields.io/github/stars/marcelverdult/meshcore-regions?style=social) | Community-editable JSON catalog of region codes used worldwide, allowing listing of public channels. | ![GitHub last commit](https://img.shields.io/github/last-commit/marcelverdult/meshcore-regions) |
| [MeshCore Utils (MC-Keygen)](https://github.com/samschlegel/meshcore-utils) ![GitHub Repo stars](https://img.shields.io/github/stars/samschlegel/meshcore-utils?style=social) | Rust vanity Ed25519 key generator with CUDA or Metal acceleration. (AI code) | ![GitHub last commit](https://img.shields.io/github/last-commit/samschlegel/meshcore-utils) |
| [MeshCore Web Key Generator](https://github.com/agessaman/meshcore-web-keygen) ![GitHub Repo stars](https://img.shields.io/github/stars/agessaman/meshcore-web-keygen?style=social) | Browser-only Ed25519 key generator with custom public-key prefixes. | ![GitHub last commit](https://img.shields.io/github/last-commit/agessaman/meshcore-web-keygen) |
| [MeshCore Web Keygen](https://gessaman.com/mc-keygen/) 🔒 | Client-side vanity Ed25519 key generator with custom hex prefixes. | |
| [Reticulum Network Planner](https://github.com/0xSeren/Reticulum-Network-Planner) ![GitHub Repo stars](https://img.shields.io/github/stars/0xSeren/Reticulum-Network-Planner?style=social) | *(Applies to all LoRa.)* Given a number of LoRa nodes and a geographical area, calculates optimal node positions from geographical data. | ![GitHub last commit](https://img.shields.io/github/last-commit/0xSeren/Reticulum-Network-Planner) |

## Firmware and Flashing

### Forks and Custom Firmware

Firmware marked 🔒 is closed source.

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [Aurora](https://forge.hackers.town/Wrewdison/Aurora) | **LilyGO T-Deck.** Standalone firmware with contact management and BLE companion support, an alternative to Ripple. | |
| [BlackJackOS](https://github.com/Robert-Proaps/BlackJackOS-BJOS-) ![GitHub Repo stars](https://img.shields.io/github/stars/Robert-Proaps/BlackJackOS-BJOS-?style=social) | **LilyGo T-Deck, T-Deck Plus.** Portable toolbox and platform for building apps and functionality, with an application-oriented standalone interface. | ![GitHub last commit](https://img.shields.io/github/last-commit/Robert-Proaps/BlackJackOS-BJOS-) |
| [chiyocore](https://github.com/kore-signet/chiyocore) ![GitHub Repo stars](https://img.shields.io/github/stars/kore-signet/chiyocore?style=social) | **Generic ESP32 with SX1262/SX1276.** Experimental Rust reimplementation of MeshCore, alternative to the C++ Arduino implementation. | ![GitHub last commit](https://img.shields.io/github/last-commit/kore-signet/chiyocore) |
| [CubeCell MeshCore](https://github.com/atomozero/CubeCellMeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/atomozero/CubeCellMeshCore?style=social) | **Heltec CubeCell HTCC-AB01, AB02, AC01** (ASR6501 + SX1262). Repeater-only firmware optimised for solar deployments: store-and-forward mailbox, mesh health monitor, remote CLI, adaptive TX power, deep sleep (~3.5 µA). | ![GitHub last commit](https://img.shields.io/github/last-commit/atomozero/CubeCellMeshCore) |
| [EastMesh](https://github.com/xJARiD/MeshCore-EastMesh) ![GitHub Repo stars](https://img.shields.io/github/stars/xJARiD/MeshCore-EastMesh?style=social) | MQTT repeater and WiFi companion builds with prebuilt releases. | ![GitHub last commit](https://img.shields.io/github/last-commit/xJARiD/MeshCore-EastMesh) |
| [EasySkyMesh](https://github.com/IoTThinks/EasySkyMesh) ![GitHub Repo stars](https://img.shields.io/github/stars/IoTThinks/EasySkyMesh?style=social) | Power-saving fork for ultra-low-power repeater and sensor deployments. | ![GitHub last commit](https://img.shields.io/github/last-commit/IoTThinks/EasySkyMesh) |
| [Fennek](https://github.com/danst0/fennek) ![GitHub Repo stars](https://img.shields.io/github/stars/danst0/fennek?style=social) | **LilyGO T-Deck Pro.** Adds music, audiobooks and eBooks alongside mesh chat. | ![GitHub last commit](https://img.shields.io/github/last-commit/danst0/fennek) |
| [FieldMesh](https://github.com/TogeriX-hub/FieldMesh) ![GitHub Repo stars](https://img.shields.io/github/stars/TogeriX-hub/FieldMesh?style=social) | **Elecrow ThinkNode M1, Seeed Wio Tracker L1** (tested). Outdoor-focused fork for festivals, hiking and off-grid events: automatic GPS advertising, Haversine tracking page, one-press Off-Grid mode, SOS alerts. | ![GitHub last commit](https://img.shields.io/github/last-commit/TogeriX-hub/FieldMesh) |
| [InkCore](https://codeberg.org/todd-herbert/InkCore) | AI-free BLE-companion firmware for small e-paper devices with configurable applets. | |
| [LunarCore](https://github.com/STCisGOOD/lunarcore) ![GitHub Repo stars](https://img.shields.io/github/stars/STCisGOOD/lunarcore?style=social) | **Heltec WiFi LoRa 32 V3 (ESP32-S3 + SX1262).** Multi-protocol Rust firmware combining MeshCore, Meshtastic and RNode/KISS (Reticulum) on one device. | ![GitHub last commit](https://img.shields.io/github/last-commit/STCisGOOD/lunarcore) |
| [MC-T5-Pro](https://github.com/dz0ny/meshcore-t5-epaper-s3-pro) ![GitHub Repo stars](https://img.shields.io/github/stars/dz0ny/meshcore-t5-epaper-s3-pro?style=social) | **LilyGo T5 ePaper S3 Pro.** A paper-like handheld MeshCore communicator. | ![GitHub last commit](https://img.shields.io/github/last-commit/dz0ny/meshcore-t5-epaper-s3-pro) |
| [MCLite](https://github.com/laserir/MCLite) ![GitHub Repo stars](https://img.shields.io/github/stars/laserir/MCLite?style=social) | **LilyGO T-Deck Plus.** Simplified firmware for non-technical users: zero-config via SD card JSON, LVGL touch UI, DMs and channels, SOS, GPS sharing, multi-language, PIN lock, SD message history. | ![GitHub last commit](https://img.shields.io/github/last-commit/laserir/MCLite) |
| [Meck](https://github.com/pelgraine/Meck) ![GitHub Repo stars](https://img.shields.io/github/stars/pelgraine/Meck?style=social) | **LilyGO T-Deck Pro, T-Deck Max, T5 E-Paper S3 Pro.** BLE and WiFi companion fork; early-stage, repeater and USB firmware still in development. | ![GitHub last commit](https://img.shields.io/github/last-commit/pelgraine/Meck) |
| [Meck-P4](https://github.com/pelgraine/Meck-P4) ![GitHub Repo stars](https://img.shields.io/github/stars/pelgraine/Meck-P4?style=social) | **LilyGo T-Display P4 (ESP32-P4).** Port of Meck to the P4 platform. | ![GitHub last commit](https://img.shields.io/github/last-commit/pelgraine/Meck-P4) |
| [Meshcomod](https://meshcomod.com/) ([GitHub repository](https://github.com/ALLFATHER-BV/meshcomod)) ![GitHub Repo stars](https://img.shields.io/github/stars/ALLFATHER-BV/meshcomod?style=social) | **Heltec and Seeed LoRa devices.** Companion firmware offering USB + Bluetooth + TCP simultaneously (phone app, web client or Home Assistant). | ![GitHub last commit](https://img.shields.io/github/last-commit/ALLFATHER-BV/meshcomod) |
| [MeshCore Cardputer ADV (sosprz)](https://github.com/sosprz/meshcore-cardputer-adv) ![GitHub Repo stars](https://img.shields.io/github/stars/sosprz/meshcore-cardputer-adv?style=social) | **M5Stack Cardputer-ADV (ESP32-S3), Cap LoRa868.** Specialized UI; flashable via M5Burner, ESP flasher tools, or web flasher. | ![GitHub last commit](https://img.shields.io/github/last-commit/sosprz/meshcore-cardputer-adv) |
| [MeshCore Cardputer ADV (Stachugit)](https://github.com/Stachugit/MeshCore-Cardputer-ADV) ![GitHub Repo stars](https://img.shields.io/github/stars/Stachugit/MeshCore-Cardputer-ADV?style=social) | **M5Stack Cardputer-ADV** with Cap LoRa868 or DX-LR30-900M22SP. Enhanced TFT UI with chat bubbles, 18 colour themes, notification popups, Bluetooth pairing. | ![GitHub last commit](https://img.shields.io/github/last-commit/Stachugit/MeshCore-Cardputer-ADV) |
| [MeshCore Cardputer-ADV (MultiMote)](https://github.com/MultiMote/meshcore-cardputer-adv) ![GitHub Repo stars](https://img.shields.io/github/stars/MultiMote/meshcore-cardputer-adv?style=social) | **M5Stack Cardputer Adv with Cap LoRa-1262.** Fork for this module combination. | ![GitHub last commit](https://img.shields.io/github/last-commit/MultiMote/meshcore-cardputer-adv) |
| [MeshCore Filter Firmware](https://github.com/jhuebert/MeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/jhuebert/MeshCore?style=social) | **All MeshCore repeater targets** (Heltec V3/V4, CT-62, Wireless Tracker; Station G2/G3; RAK4631/3401; SenseCap Solar; XIAO ESP32-S3/nRF52; T1000-E; Generic E22 SX1262). Remotely configurable drop/forward rules by channel, sender, text, packet type, hops, region and signal strength over the repeater CLI; per-rule throttling, advert rate limiting, saved-airtime telemetry, battery voltage gate. Prebuilt firmware on Releases (filter-v* tags); guide in FILTER.md. | ![GitHub last commit](https://img.shields.io/github/last-commit/jhuebert/MeshCore) |
| [MeshCore Low-Power](https://github.com/dt267/MeshCore-Low-Power-Firmware-For-Heltec-V3-V4) ![GitHub Repo stars](https://img.shields.io/github/stars/dt267/MeshCore-Low-Power-Firmware-For-Heltec-V3-V4?style=social) | **Heltec V3/V4.** Deep-sleep builds with BLE, USB and WiFi in one image. | ![GitHub last commit](https://img.shields.io/github/last-commit/dt267/MeshCore-Low-Power-Firmware-For-Heltec-V3-V4) |
| [MeshCore mishmesh](https://github.com/burakcan/MeshCore-mishmesh) ![GitHub Repo stars](https://img.shields.io/github/stars/burakcan/MeshCore-mishmesh?style=social) | On-device UI making a companion radio usable without a paired phone. | ![GitHub last commit](https://img.shields.io/github/last-commit/burakcan/MeshCore-mishmesh) |
| [MeshCore PaperUI](https://github.com/dz0ny/meshcore-paperui) ![GitHub Repo stars](https://img.shields.io/github/stars/dz0ny/meshcore-paperui?style=social) | E-paper handheld firmware with standalone messaging, GPS and maps. | ![GitHub last commit](https://img.shields.io/github/last-commit/dz0ny/meshcore-paperui) |
| [MeshCore Solo](https://github.com/MarekZegare4/MeshCore-Solo) ![GitHub Repo stars](https://img.shields.io/github/stars/MarekZegare4/MeshCore-Solo?style=social) | **Seeed Studio Wio Tracker L1 (OLED and eInk), GAT562 30S Mesh Kit.** Standalone firmware based on the official companion firmware, adding offline GPS navigation and GPX export. | ![GitHub last commit](https://img.shields.io/github/last-commit/MarekZegare4/MeshCore-Solo) |
| [MeshCore T-beam-1W](https://github.com/mintylinux/Meshcore-T-beam-1W-Firmware) ![GitHub Repo stars](https://img.shields.io/github/stars/mintylinux/Meshcore-T-beam-1W-Firmware?style=social) | **LilyGO T-Beam 1 Watt** (SX1262, ESP32). Ported firmware with device-specific fixes for battery, boot loops and the 1W PA; includes a web flasher. | ![GitHub last commit](https://img.shields.io/github/last-commit/mintylinux/Meshcore-T-beam-1W-Firmware) |
| [MeshCore TEAM enhanced firmware](https://github.com/tmacinc/MeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/tmacinc/MeshCore?style=social) | **Autonomous tracker custom firmware.** Layered on stock MeshCore, adding team-oriented GPS tracking, smart forwarding control and unattended autonomous operation. | ![GitHub last commit](https://img.shields.io/github/last-commit/tmacinc/MeshCore) |
| [MeshCore Wio Tracker L1 Pro (sosprz)](https://github.com/sosprz/Meshcore-Wio-Tracker-L1-Pro) ![GitHub Repo stars](https://img.shields.io/github/stars/sosprz/Meshcore-Wio-Tracker-L1-Pro?style=social) | **Seeed Studio Wio Tracker L1 Pro.** On-device companion UI with UF2 drag-and-drop and web flasher support. | ![GitHub last commit](https://img.shields.io/github/last-commit/sosprz/Meshcore-Wio-Tracker-L1-Pro) |
| [MeshcoreGRID](https://github.com/Quark1980/MeshcoreGRID) ![GitHub Repo stars](https://img.shields.io/github/stars/Quark1980/MeshcoreGRID?style=social) | **Heltec WiFi LoRa 32 V4 TFT** (ESP32-S3, FT6336 touchscreen). Touch-first UI with Messenger (DM + channel chat, ACK tracking), Discover (advert browser), Radio/BLE/Settings/Power apps, pinch-to-zoom Map. BETA. | ![GitHub last commit](https://img.shields.io/github/last-commit/Quark1980/MeshcoreGRID) |
| [MeshCoreNG](https://github.com/MichTronics/MeshCoreNG) ![GitHub Repo stars](https://img.shields.io/github/stars/MichTronics/MeshCoreNG?style=social) | Dutch fork focused on smarter repeaters for larger, busier meshes. | ![GitHub last commit](https://img.shields.io/github/last-commit/MichTronics/MeshCoreNG) |
| [MeshCoreTel](https://github.com/VBart/MeshCoreTel-firmware) ![GitHub Repo stars](https://img.shields.io/github/stars/VBart/MeshCoreTel-firmware?style=social) | Repeater fork of EastMesh with WiFi, HTTPS API, web panel and MQTT. | ![GitHub last commit](https://img.shields.io/github/last-commit/VBart/MeshCoreTel-firmware) |
| [MeshCoreTerm (Dabeani)](https://github.com/dabeani/meshcoreterm) ![GitHub Repo stars](https://img.shields.io/github/stars/dabeani/meshcoreterm?style=social) | **LilyGO T-Deck, T-Deck Plus, Seeed Studio SenseCap Indicator (TFT/D1Pro).** Retro-themed, touch-first UI: tabbed interface (Contacts, Channels, Map, Mgmt), slippy tile map, D-pad/trackball support, RSSI/SNR display, telemetry. | ![GitHub last commit](https://img.shields.io/github/last-commit/dabeani/meshcoreterm) |
| [MeshPunk](https://github.com/PhilMo6/meshpunk) ![GitHub Repo stars](https://img.shields.io/github/stars/PhilMo6/meshpunk?style=social) | **LilyGo T-Deck.** LVGL and Lua handheld firmware. | ![GitHub last commit](https://img.shields.io/github/last-commit/PhilMo6/meshpunk) |
| [MeshUltra](https://tdeck.ubnzeek.com/) 🔒 | **LilyGo T-Deck, T-Deck+.** Firmware for both devices. | |
| [Offband Mesh](https://github.com/OffbandMesh/meshcore-firmware) ![GitHub Repo stars](https://img.shields.io/github/stars/OffbandMesh/meshcore-firmware?style=social) | Cross-role firmware enhancements and optimisation. | ![GitHub last commit](https://img.shields.io/github/last-commit/OffbandMesh/meshcore-firmware) |
| [Saitama](https://github.com/868meshbot/Saitama) ![GitHub Repo stars](https://img.shields.io/github/stars/868meshbot/Saitama?style=social) | **LilyGo T-Deck, T-Deck Plus.** Standalone firmware for LoRa mesh devices, built on MeshCore. | ![GitHub last commit](https://img.shields.io/github/last-commit/868meshbot/Saitama) |
| [SigurdOS T-Deck](https://github.com/hermes-gadget/SigurdOS-tdeck) ![GitHub Repo stars](https://img.shields.io/github/stars/hermes-gadget/SigurdOS-tdeck?style=social) | Launcher-style touch UI for the T-Deck with maps and over-the-air updates. GPL-3.0-or-later. | ![GitHub last commit](https://img.shields.io/github/last-commit/hermes-gadget/SigurdOS-tdeck) |
| [TapTap Firmware (T1000-E)](https://github.com/mtoolstec/TapTapFW) ![GitHub Repo stars](https://img.shields.io/github/stars/mtoolstec/TapTapFW?style=social) | **Seeed Studio T1000-E, RAK WisMesh Tag.** Headless button-interaction firmware: canned messages, Morse entry, GPS toggle, RTTTL/CW buzzer alerts. | ![GitHub last commit](https://img.shields.io/github/last-commit/mtoolstec/TapTapFW) |
| [Trail Mate](https://github.com/vicliu624/trail-mate) ![GitHub Repo stars](https://img.shields.io/github/stars/vicliu624/trail-mate?style=social) | **LilyGO T-LoRa-Pager, T-Deck** (primary); M5Stack Tab5, T-Display P4 (bring-up); T-Watch S3 (experimental). Offline-first navigation with offline GPS maps, Meshtastic + MeshCore messaging, SSTV receiver, FSK+Codec2 walkie-talkie, ESP-NOW team mode, Sub-GHz sweep. | ![GitHub last commit](https://img.shields.io/github/last-commit/vicliu624/trail-mate) |
| [Wadamesh](https://www.wadamesh.com/) ([GitHub repository](https://github.com/ALLFATHER-BV/wadamesh)) ![GitHub Repo stars](https://img.shields.io/github/stars/ALLFATHER-BV/wadamesh?style=social) | **Heltec V4 TFT/touch, LilyGo T-Deck.** Standalone LVGL touch UI: on-device chat, channels, rooms, contacts, live map, OTA updates, no phone required. Split out of Meshcomod. | ![GitHub last commit](https://img.shields.io/github/last-commit/ALLFATHER-BV/wadamesh) |
| [ZephCore](https://github.com/liquidraver/ZephCore) ![GitHub Repo stars](https://img.shields.io/github/stars/liquidraver/ZephCore?style=social) | **nRF52840:** Wio Tracker L1, Seeed T1000-E, RAK4631, RAK WisMesh Tag, ThinkNode M1, Ikoka Nano 30dBm. **ESP32:** XIAO ESP32-C3/C6, Station G2, LilyGo TLoRa C6. **Other:** XIAO nRF54L15, XIAO MG24. Port from Arduino to Zephyr RTOS: WFI sleep, adaptive contention window, CAD-based RX duty cycling, UF2/DFU. | ![GitHub last commit](https://img.shields.io/github/last-commit/liquidraver/ZephCore) |

### Flashing and Updating

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [Drone MeshCore Updater](https://github.com/recrof/drone_meshcore_updater) ![GitHub Repo stars](https://img.shields.io/github/stars/recrof/drone_meshcore_updater?style=social) | Zephyr firmware for Seeed XIAO boards that carries firmware bundles to unreachable repeaters by drone or on foot and flashes over BLE DFU, with a PWA web client. | ![GitHub last commit](https://img.shields.io/github/last-commit/recrof/drone_meshcore_updater) |
| [Heltec V4.2 Multi-Boot Selector](https://github.com/Finmacjones/HeltecV4.2MultiBoot) ![GitHub Repo stars](https://img.shields.io/github/stars/Finmacjones/HeltecV4.2MultiBoot?style=social) | **Heltec WiFi LoRa 32 V4.2 (ESP32-S3).** 4 OTA slots (3 MB each) in 16 MB flash; switches between Meshtastic, MeshCore, RNode and a spare slot via OLED menu and USER button, with per-firmware NVS/filesystem isolation. | ![GitHub last commit](https://img.shields.io/github/last-commit/Finmacjones/HeltecV4.2MultiBoot) |
| [Mesh America Device Configurator](https://meshamerica.com/device-configurator/) 🔒 | Browser flasher and configurator over Web Serial. | |
| [Mesh Loader](https://github.com/eliahreeves/mesh-loader) ![GitHub Repo stars](https://img.shields.io/github/stars/eliahreeves/mesh-loader?style=social) | **Heltec WiFi LoRa 32 V3/V4** (other 8 MB+ flash ESP32 devices can be added). "Dual Boot" firmware switching between MeshCore and Meshtastic at boot via a 2-second button press, with isolated NVS/filesystem data per firmware. | ![GitHub last commit](https://img.shields.io/github/last-commit/eliahreeves/mesh-loader) |
| [MeshCore Custom Firmware Builder](https://github.com/christian45410/meshcore-cfw-builder) ![GitHub Repo stars](https://img.shields.io/github/stars/christian45410/meshcore-cfw-builder?style=social) | **All MeshCore-supported ESP32 boards.** Web-based firmware builder: select board, firmware type and custom flags, get a compiled .bin back. | ![GitHub last commit](https://img.shields.io/github/last-commit/christian45410/meshcore-cfw-builder) |
| [MeshCore Drone Updater](https://github.com/lucidnx/meshcore-drone-updater) ![GitHub Repo stars](https://img.shields.io/github/stars/lucidnx/meshcore-drone-updater?style=social) | Raspberry Pi service for drive-by or drone-assisted DFU updates of physically unreachable nodes. | ![GitHub last commit](https://img.shields.io/github/last-commit/lucidnx/meshcore-drone-updater) |
| [MeshCore-OTA-Flasher](https://github.com/Dreikor17/MeshCore-OTA-Flasher) ![GitHub Repo stars](https://img.shields.io/github/stars/Dreikor17/MeshCore-OTA-Flasher?style=social) | Windows tool for nRF52840 firmware updates over Bluetooth LE. | ![GitHub last commit](https://img.shields.io/github/last-commit/Dreikor17/MeshCore-OTA-Flasher) |
| [MeshFirmware](https://github.com/mikecarper/meshfirmware) ![GitHub Repo stars](https://img.shields.io/github/stars/mikecarper/meshfirmware?style=social) | Interactive Windows and Linux scripts for selecting, flashing and compiling releases. | ![GitHub last commit](https://img.shields.io/github/last-commit/mikecarper/meshfirmware) |
| [MeshForge](https://github.com/MeshEnvy/mesh-forge) ![GitHub Repo stars](https://img.shields.io/github/stars/MeshEnvy/mesh-forge?style=social) | Cloud firmware builder and web flasher for LoRa mesh devices. | ![GitHub last commit](https://img.shields.io/github/last-commit/MeshEnvy/mesh-forge) |
| [MeshCore OTA guide](https://github.com/Mraanderson/meshcore-ota) ![GitHub Repo stars](https://img.shields.io/github/stars/Mraanderson/meshcore-ota?style=social) | Step-by-step OTA firmware update guide for repeaters and room servers. | ![GitHub last commit](https://img.shields.io/github/last-commit/Mraanderson/meshcore-ota) |
| [Python Nordic Legacy DFU Tool](https://github.com/recrof/nrf_dfu_py) ![GitHub Repo stars](https://img.shields.io/github/stars/recrof/nrf_dfu_py?style=social) | Cross-platform nRF51/nRF52 Bluetooth DFU tool with GUI and CLI. | ![GitHub last commit](https://img.shields.io/github/last-commit/recrof/nrf_dfu_py) |
| [weebl2000's Firmware Builder](https://mcimages.weebl.me/) 🔒 | **All MeshCore-supported boards.** Build and download firmware images for your device. | |
| [XIAO nRF52 Updater](https://github.com/recrof/xiao_nrf52_updater) ![GitHub Repo stars](https://img.shields.io/github/stars/recrof/xiao_nrf52_updater?style=social) | Updater firmware that flashes nearby nRF52 nodes over Bluetooth DFU. | ![GitHub last commit](https://img.shields.io/github/last-commit/recrof/xiao_nrf52_updater) |

## Hardware

### Supported Devices

Compatibility references; check these before buying a board.

| Resource | Description |
| :--- | :--- |
| [Mesh America supported hardware](https://wiki.meshamerica.com/books/meshcore/page/supported-hardware-for-meshcore) | Community list of compatible boards and chipsets. |
| [mesh-sn.de firmware matrix](https://mesh-sn.de/en/devices/matrix) | Per-device matrix of which MeshCore firmware builds are available. |
| [MeshCore Europe devices](https://meshcoreeurope.org/en/devices/) | Multilingual device directory with setup guides. |
| [LocalMesh UK devices](https://localmesh.co.uk/devices/) | Device guides for the UK emergency network. |

### Pre-built Devices

Sold with MeshCore firmware pre-installed, or with MeshCore selectable at order.

| Product | Description |
| :--- | :--- |
| [Seeed Wio Tracker L1 Pro for MeshCore](https://www.seeedstudio.com/Wio-Tracker-L1-Pro-for-Meshcore-p-6717.html) | Handheld with GPS, OLED display and battery. |
| [SenseCAP Solar Node P1 Pro for MeshCore](https://www.seeedstudio.com/SenseCAP-Solar-Node-P1-Pro-for-Meshcore-p-6741.html) | Solar-powered outdoor repeater with GPS. |
| [Seeed MeshCore Starter Kit](https://www.seeedstudio.com/MeshCore-Starter-Kit-Ready-to-Use-Off-Grid-Instant-Reliable-Communication.html) | Bundle of a repeater and client nodes ready to deploy. |
| [RAK WisMesh Tag (Atlavox)](https://atlavox.com/products/wismesh-tag-meshtastic-meshcore-radio) | IP66 GPS tracker; choose the MeshCore variant when ordering. |
| [Elecrow ThinkNode M9](https://www.elecrow.com/thinknode-m9-meshcore-communication-terminal-with-full-keyboard-2-4inch-lcd-esp32-s3-lr1110-gps-2300mah.html) | Standalone communicator with QWERTY keyboard, colour LCD and GPS. |
| [LilyGo T-LoRa Pager MeshCore](https://lilygo.cc/products/t-lora-pager-meshcore) | Pocket pager with keyboard, display and LR1121 radio. |

### DIY Builds

Open designs with published files (PCB, BOM, STL or detailed build guide).

| Project | Description |
| :--- | :--- |
| [915 MHz Mesh Antenna](https://github.com/ellisgl/915-mesh-antenna) ![GitHub Repo stars](https://img.shields.io/github/stars/ellisgl/915-mesh-antenna?style=social) | Stacked collinear antenna with simulation files and build dimensions. |
| [bardolf MeshCore Repeater](https://github.com/bardolf/meshcore-repeater) ![GitHub Repo stars](https://img.shields.io/github/stars/bardolf/meshcore-repeater?style=social) | Solar repeater with FreeCAD enclosure, STL files and full BOM. |
| [LoRaMeshNodes](https://github.com/hotwolf/LoRaMeshNodes) ![GitHub Repo stars](https://img.shields.io/github/stars/hotwolf/LoRaMeshNodes?style=social) | Mobile and solar nodes with OpenSCAD enclosures, STL files and BOMs. |
| [MeshCore E22P Repeater](https://github.com/Sukecz/MeshCore-E22P-Repeater) ![GitHub Repo stars](https://img.shields.io/github/stars/Sukecz/MeshCore-E22P-Repeater?style=social) | XIAO ESP32-S3 repeater with an Ebyte E22P module, wiring and firmware. |
| [NodakMesh solar repeater build](https://nodakmesh.org/blog/meshcore-solar-repeater-build) | Parts list, solar sizing, weatherproofing and configuration walkthrough. |
| [RePeter](https://github.com/robrec/MeshCoreRepeater-RePeter) ![GitHub Repo stars](https://img.shields.io/github/stars/robrec/MeshCoreRepeater-RePeter?style=social) | Bremen repeater board with Gerbers, schematics, BOM and STEP model. |
| [XIAO S3 Dual-Radio Repeater](https://github.com/bouyous/meshcore-xiao-s3-dual-radio-repeater) ![GitHub Repo stars](https://img.shields.io/github/stars/bouyous/meshcore-xiao-s3-dual-radio-repeater?style=social) | Two-radio summit repeater with assembly guide and field test reports. |

### Enclosures and Mounts

| Project | Description |
| :--- | :--- |
| ["Ray" Heltec V3 case](https://www.thingiverse.com/thing:7395161) | Handheld case with room for one 18650 cell. |
| [Case-Stick for ProMicro nRF52](https://www.thingiverse.com/thing:7394936) | Stick-shaped case for ProMicro nRF52840 boards. |
| [The Corebell](https://www.printables.com/model/1490873-the-corebell-a-meshcoremeshtastic-solar-node) | Printable solar node enclosure. |
| [Heltec T114 case with battery](https://www.thingiverse.com/thing:7390213) | Compact handheld case with an integrated battery bay. |
| [MeshCore mast enclosure for Heltec V3](https://www.printables.com/model/1767610-meshcore-mast-enclosure-heltec-v3) | Mast-mounted outdoor enclosure. |
| [NodakMesh enclosures guide](https://nodakmesh.org/meshcore/enclosures) | Overview of commercial and DIY cases with IP-rating guidance. |
| [Outdoor Case for MeshCore Node / Repeater](https://www.thingiverse.com/thing:7383479) | Printable weatherproof repeater case. |

## Maps and Diagnostics

Tools to see what is happening on the mesh.

### Maps

| Project / URL | Description |
| :--- | :--- |
| [#BEmesh map](https://meshmap.radio-actief.be/) | Belgian map with network stats and a configurator. |
| [Czech coverage map](https://pokryti.meshcore.cz/) | Czech coverage with terrain-aware planning. |
| [HanseMesh map](https://hansemesh.de/netzwerk/karte/) | Northern Germany repeater status and coverage. |
| [HopRadar](https://hopradar.net/) | Browser live map and analyzer for your own node over BLE or USB, with hop traces and SNR. |
| [Iceland analyzer](https://mc.flatuslifir.is/) | Live CoreScope instance for the Icelandic network. |
| [KernWi-Fi map](https://meshcore.kernwifi.com.au/map) | South Australian repeater and observer network. |
| [KiekR map](https://map.kiekr.app/) | Region coverage derived from neighbour observations uploaded by KiekR users. |
| [LocalMesh Germany map](https://localmesh.de/karte/) | German coverage with repeater directory. |
| [LocalMesh Netherlands map](https://localmesh.nl/en/map/) | Dutch network coverage. |
| [LoraMesh France map](https://loramesh.fr/carte/) | French coverage by region. |
| [m3sh.uk Map](https://m3sh.uk/contacts/) | UK network as seen from Oxfordshire. |
| [map.meshradio.uk](https://map.meshradio.uk/) | Network analysis and visualization tool for the UK MeshRadio community. |
| [mapme.sh](https://mapme.sh/) | Crowdsourced coverage mapping with companion wardriving apps. |
| [MeshCore Europe map](https://meshcoreeurope.org/en/map/) | European repeater and room server coverage. |
| [MeshCore Map](https://map.meshcore.dev/) | Official global map displaying static user uploads for repeaters and room servers. |
| [MeshCore Polska map](https://mapa.meshcorepolska.org/) | Polish clients, repeaters, room servers and sensors. |
| [MeshCore-de.fyi region map](https://umap.openstreetmap.de/en/map/meshcore-defyi_130650) | Editable uMap of regions, mainly Germany. See also [region-editing context](https://meshcore-de.fyi/meshcore:allgemeines:regions:reale-regions-in-repeatern) and [how to edit](https://meshcore-de.fyi/region_karte). |
| [MeshMapper](https://meshmapper.net/) | Wardriving coverage platform with regional instances and an open API. |

### Diagnostics and Dashboards

| Project / URL | Description |
| :--- | :--- |
| [Belgian MQTT analyzer](https://analyzer.on8ar.eu/) | CoreScope instance for Belgian traffic. |
| [Boston MeshCore MQTT dashboard](https://mcmqttdashboard.bostonme.sh/) | Live MQTT node presence and traffic metrics. |
| [EU Meshcore Analyzer](https://meshcore-analyzer.eu/) | Live visual map of European MeshCore LoRa network traffic. |
| [KernWi-Fi live telemetry](https://meshcore.kernwifi.com.au/live) | South Australian live activity feed. |
| [MeshCore Analyzer (letsmesh)](https://analyzer.letsmesh.net/) | Node connectivity, packet analysis and mesh health metrics. |
| [MeshCore Observers](https://meshcore.observer) | Growing directory of public collectors, reporters and analyzers. |
| [MeshCore Tools](https://meshcore.envoyage.io/) | Repeater configurator and region code lookup helpers. |
| [MeshCore Wall of Shame](https://advertrank.com/) | Tongue-in-cheek ranking of the nodes flooding the mesh with adverts. |
| [meshcoresim.com](https://www.meshcoresim.com/) | Simulation tool for modeling message propagation and testing network scalability. |
| [Meshcoretel.io](https://meshcoretel.io/) | Public telemetry: live packet map, propagation trees, link load, wardrive coverage, region/mesh selection, node and observer directories, stats dashboards, channels view, prefix explorer. |
| [MeshRank](https://meshrank.net/) | Leaderboard and analytics for repeaters and routes, mainly in the UK. |
| [TennMesh Live](https://live.tennmesh.com/) | Tennessee telemetry with RF link analysis and routing loop detection. |

### RF Planning

| Project / URL | Description |
| :--- | :--- |
| [contempl8 Relief](https://contempl8.io/tools/relief/) | Free browser 3D terrain block viewer for inspecting the landform around a site; can be slow on large areas. |
| [contempl8 Topo](https://contempl8.io/tools/topo/) | Free browser elevation profile along a drawn line, useful for rough line-of-sight checks. |
| [HopReach](https://github.com/A13xB0/hopreach) | Browser-based terrain-aware RF planning and MeshCore simulator: realistic LoRa coverage maps, packet propagation, collisions, repeater behaviour, airtime contention, preamble lock failures, hidden-node effects, scalability. |
| [Mesh Community Planner](https://github.com/PapaSierra555/MeshCommunityPlanner) | Desktop planner with terrain-aware propagation, hardware selection and bill of materials. |
| [MeshBench](https://github.com/MeshBench/meshbench) | RF-accurate simulation and development toolkit running real firmware against a sample-accurate LoRa channel and real terrain; network planning, firmware A/B testing, board emulation, CI fixtures, Wireshark/pcapng and SDR/IQ integration. [Site](https://meshbench.github.io/) |
| [meshrf.net](https://meshrf.net/) | RF propagation and link analysis tool designed for LoRa Mesh. |
| [MeshKit](https://meshkit.app/) | Browser site planner with terrain LOS, Fresnel analysis and BLE radio tools. |
| [MeshOMatic](https://map.meshomatic.net/) | Terrain-aware repeater placement planning and topology analysis. |
| [Reticulum Network Planner](https://github.com/0xSeren/Reticulum-Network-Planner) | *(Applies to all LoRa.)* See [Utilities](#utilities). |

## Guides and Learning

| Resource | Description |
| :--- | :--- |
| [Andy Kirby on YouTube](https://www.youtube.com/@andykirby) | Hardware reviews, repeater builds and firmware walkthroughs. |
| [Austin Mesh setup guide](https://www.austinmesh.org/join/meshcore-setup/) | Beginner-friendly local setup. |
| [Bravo.TAKKE.me MeshCore book](https://bravo.takke.me/books/meshcore) | Traditional Chinese guide: quick start, basic setup, firmware types, how MeshCore differs from Meshtastic. |
| [J-Rat Techworks repeater guide](https://jrattechworks.com/meshcore-repeater-flashing-guide/) | Flashing and repeater setup. |
| [Kev's Robots MeshCore course](https://www.kevsrobots.com/learn/meshcore/) | Structured tutorial series from basics to flashing. |
| [LitBomb's MeshCore FAQ](https://github.com/LitBomb/MeshCore-FAQ) | Community FAQ in English and German. |
| [LocalMesh NL setup guide](https://www.localmesh.nl/en/meshcore-setup/) | Dutch-language beginner guide. |
| [Mesh America wiki](https://wiki.meshamerica.com/books/meshcore/page/start-here-meshcore-guide) | Guides and protocol overview. |
| [Mesh Sorocaba configuração](https://www.meshsorocaba.org/configuracao/) | Portuguese-language setup documentation. |
| [Meshcore region info](https://github.com/luckystriike22/meshcore_region_info) | Reference on MeshCore region codes and how they're used. |
| [MeshCore Europe getting started](https://meshcoreeurope.org/en/get-started/) | Multilingual introduction. |
| [MeshCore Europe repeater guide](https://meshcoreeurope.org/en/repeater-guide/) | Repeater deployment walkthrough. |
| [MeshCore Ninja](https://meshcore.ninja/) | Open catalog of regional networks, devices, firmwares and software. |
| [NodakMesh wiki](https://nodakmesh.org/meshcore/wiki) | Reference documentation and setup guides. |
| [ScotMesh getting started](https://wiki.scotmesh.uk/en/MeshCore/getting-started) | Beginner guide from unboxing to the first message. |
| [Video: MeshCore Quickstart](https://youtube.com/playlist?list=PLshzThxhw4O4WU_iZo3NmNZOv6KMrUuF9) | The comms channel's quickstart playlist. |
| [Video: How to get started](https://youtu.be/t1qne8uJBAc) | Getting-started walkthrough. |
| [Why MeshCore needs regions - explained simply](https://kiekr.app/why-regions) | Plain-language explanation of the region system. |
| [WISSEN TECHNIK podcast](https://wissen-technik-meshcore-meshtastic.podigee.io/) | German-language podcast on MeshCore and Meshtastic. |

## Communities

### Virtual

- [LetsMesh Forum](https://forum.letsmesh.net/) - Community forum for MeshCore and LoRa mesh, with regional sub-forums.
- [MeshCore subreddit](https://old.reddit.com/r/meshcore/) - Community discussion.
- [Meshcore.io Discord](https://meshcore.gg/) - Official server; many regional channels exist within it.

### Country / region Websites

#### Australia

- [Brisbane and SEQ](https://wiki.mbug.com.au/en/Meshcore/Settings)
- [East Mesh](https://eastmesh.au/)
- [MeshCore Western Australia](https://perth.meshcore.au/)
- [MeshCore AUS wiki](https://wiki.meshcoreaus.org/)
- [Mesh Sydney](https://meshsydney.com/)
- [NSW Mesh](https://nswmesh.au/)
- [Meshore Australia Discord](https://discord.gg/2NxehNDGT)
- [Canberra Mesh Community Discord](https://discord.gg/YeGhbsWhQD) (ACT and south NSW)

#### Austria

- [MeshCore Austria](https://meshcore.at/) - Documentation and setup guides.
- [Meshcore-Austria.at](https://www.meshcore-austria.at/doku.php?id=start) - Community wiki.
- [CarinthiaMesh wiki](https://wiki.carinthiamesh.com/)
- [MeshCore AT Telegram group](https://t.me/meshcoreat)

#### Belarus

- [MeshNetBY](https://mesh-net.by/) - Setup guides and city Telegram groups; also covers Meshtastic.

#### Belgium

- [Radio-Actief MeshCore Community](https://meshcore.radio-actief.be/) (mainly Flanders and Brussels area)
- [Radio-Actief MeshCore Documentation](https://docs.radio-actief.be/nl/MeshCore)
- [LoraMesh België](https://www.loramesh.be/) - Emergency communication network.
- [Meshpot](https://meshpot.be) - Bilingual (FR/EN) guide for Brussels residents to join MeshCore and communicate off-grid, with a focus on privacy, surveillance resistance and self-protection.
- [Radio-Actief MeshCore Discord](https://discord.gg/kvybAgqnhD) (mainly Dutch/Flemish speaking)

#### Brazil

- [Mesh Sorocaba](https://www.meshsorocaba.org/)
- [MeshCore Brasil Telegram group](https://t.me/meshcorebrasil)

#### Bulgaria

- [MeshCore Bulgaria](https://www.meshcore.bg/) - Map, presets and Telegram group.

#### Canada

- [CascadiaMesh](https://cascadiamesh.org/) - Pacific Northwest, covers British Columbia, Western Washington and Western Oregon.
- [Greater Ottawa Mesh](https://ottawamesh.ca/)
- [MeshCore Canada](https://meshcore.ca/) - National site with provincial communities.
- [Montreal Mesh](https://www.montrealmesh.ca/en/)
- [Ridgeline Mesh](https://ridgeline.ve7kod.ca/) - Southwest British Columbia, alternate frequency to Salish Mesh.
- [Salish Mesh](https://salishmesh.net/) - Salish Sea region of southwest British Columbia.

#### Chile

- [MeshChile](https://meshchile.cl/) - Guides, Discord and a [GitHub org](https://github.com/Mesh-Chile).

#### Czech Republic

- [MeshCore ČR](https://meshcore.cz/)

#### Europe

- [MeshCore Europe](https://meshcoreeurope.org/) - Multilingual umbrella site with community directory, guides and maps.

#### Finland

- [Mesh Pirkanmaa](https://meshpirkanmaa.org/) - Tampere region, including Nokia, Pirkkala and Ylöjärvi.

#### France

- [LoraMesh France](https://loramesh.fr/)
- [MeshCore France](https://www.meshcore.fr/)
- [MeshCore Paris](https://meshcore.paris/)
- [Île-de-France Mesh](https://wiki.mesh-idf.fr) - Also covers Meshtastic.
- [MeshCore France Discord](https://discord.gg/GNAfMf7nVw)

#### Germany

- [MeshCore Deutschland wiki](https://meshcore-de.fyi/) - Wiki hub with setup guides and regional group directory.
- [BSmesh](https://bsmesh.de/) - Greater Braunschweig network.
- [HanseMesh](https://hansemesh.de/) - Northern Germany network and tutorials.
- [IsarMesh](https://isarmesh.de/) - Bavarian community forum.
- [LocalMesh Deutschland](https://www.localmesh.de/)
- [Mesh Dresden](https://meshdresden.eu/)
- [Mesh Rheinland](https://www.meshrheinland.de/)
- [MeshCore Dresden](https://loramesh-dresden.de/)
- [MeshCore Essen-Kettwig](https://jonathansalim.de/)
- [MeshMitte](https://msh3.de/) - Central Germany.
- [Münsterland Mesh](https://mcml.info/)
- [SaarMesh](https://saarmesh.de/)
- [MeshCore DE Matrix room](https://matrix.to/#/#meshcore-netzwerk-de:matrix.org)
- [MeshCore DE Telegram group](https://t.me/meshcorede)
- [MeshCore-DE Signal group](https://signal.group/#CjQKIFhhdRM1Aeju45MYU8CWOkytMM8E741caAtrSvkDRaJ3EhBu5zU7KUA4w3ad35lIi8Su)
- [MeshCore DE Discord](https://discord.gg/uTMJQhh2P5)
- [MeshCore DE WhatsApp group](https://chat.whatsapp.com/KDintomf4QoCu2GkPrnIn1)

#### Greece

- [MeshCore-Greece CoreScope Map](https://meshcore-greece.up.railway.app/#/live)
- [MeshCore-Greece Discord](https://discord.gg/6KSQBqaTmw)

#### Hungary

- [MeshCore Hungary](https://mc868.hu/) - Community on 868 MHz with map and Telegram group.

#### Ireland

- [LoRa Project Ireland](https://loraproject.ie/)
- [Mayo Mesh](https://mayomesh.net/#/)
- [Mesh Radio Ireland (N&S) Discord](https://discord.gg/kraQFkpU)

#### Italy

- [MeshCore ITA](https://meshcore-ita.github.io/) - Setup guide, shared Italian radio preset, hardware, CLI reference, troubleshooting, FAQ, glossary.
- [MeshCore Italia](https://www.meshcoreitalia.it) - Nationwide mesh on the EU/UK narrow preset, with map and Telegram group.
- [LoRa Brescia](https://www.lorabrescia.it/) - Italian flashing/config guides; also covers Meshtastic and LoRa APRS.
- [MeshCore ITA Telegram group](https://t.me/meshcore_ita) - Per-region topics.
- [MeshCore Repeater Guide Italia](https://codeberg.org/3yte/meshcore-italia) - CLI guide for repeaters, regional scope tree and [command wizard](https://3yte.codeberg.page/meshcore-italia/).

#### Kazakhstan

- [MeshCore Kazakhstan](https://meshcore.kz/)
- [Kazakhstan Telegram group](https://t.me/MeshCoreKZ)

#### Latvia

- [Apraide.lv](https://apraide.lv/) - Also covers Meshtastic.

#### Lithuania

- [Atviras Tinklas](https://atvirastinklas.lt) - CoreScope instance and Telegram group.

#### Netherlands

- [Dutch MeshCore](https://dutchmeshcore.nl/) - Node directory and radio preset reference.
- [LocalMesh Nederland](https://www.localmesh.nl/)
- [MeshCore Forum NL](https://forum.meshcore-net.nl/)
- [MeshCore Nederland](https://www.meshcore.nl/)
- [MeshWiki NL](https://meshwiki.nl/)
- [Dutch MeshCore Telegram](https://t.me/meshcorenet)
- [Dutch MeshCore Discord](https://discord.com/channels/1343693475589263471/1345472768669384714)

#### New Zealand

- [Meshed](https://meshed.kiwi/)

#### Norway

- [MeshWiki.no](https://meshwiki.no/) - Documentation hub and preset reference.
- [Norway MeshCore Discord](https://discord.gg/ghVR7VGqgB)

#### Poland

- [LoRa MeshCore Polska](https://lorameshcore.pl/) - Nationwide network on the EU/UK narrow preset.
- [MeshCore Podlasie](https://meshcore.podlasie.pl/) - Podlasie region, with news, settings and a forum.
- [MeshCore Polska](https://meshcorepolska.org/)
- [MeshGo](https://meshgo.pl/)

#### Portugal

- [MeshCore Portugal](https://meshcore.pt/)

#### Romania

- [Brașov Mesh](https://brasovmesh.com/) - EU/UK narrow preset.
- [MeshCore Iași](https://meshcore-iasi.ro/) - Live dashboard.

#### Russia

- [MeshCore Moscow](https://meshcoretel.ru/) - Live telemetry map.
- [MeshCore Moscow Telegram group](https://t.me/meshcoremoscow)

#### Slovakia

- [MeshCore Slovensko](https://mesh.om3kff.sk/) - Map and Discord.

#### Slovenia

- [MeshCore Slovenija](https://meshcore.si/) - Regional preset and firmware links.

#### Spain

- [MeshCore Catalunya](https://docs.livemap-meshcorecat.com/) - Live map and documentation (also known as [Meshcore Catalonia](https://meshcore.cat/)).
- [NomadMesh](https://nomadmesh.org/) - Alpujarra region.
- [Red Sierra Sur](https://sierrasur.github.io/) - Jaén province.
- [RegionMesh España](https://www.regionmesh.com/es/) - Spanish-language hub and guides.

#### Sweden

- [Meshat.se](https://meshcore.meshat.se/)

#### Switzerland

- [MeshCore Switzerland](https://www.meshcore.ch/)

#### Ukraine

- [MeshCore UA (Kyiv)](https://meshcore.kiev.ua/)
- [MeshCore Ukraine](https://meshcore-ua.net/) - Volunteer-run public mesh for resilient communication.

#### United Kingdom

- [IPNet](https://ipnt.uk/) - Ipswich hub with CoreScope dashboards and MQTT services.
- [LocalMesh UK](https://localmesh.co.uk/) - UK emergency network with city communities.
- [MeshCore Wales](https://meshcore.wales/) - Welsh regional settings and coordination.
- [MeshHub UK](https://meshhub.uk/) - National coordination platform.
- [NorthMesh](https://northmesh.co.uk/) - Northern England.
- [ScotMesh](https://wiki.scotmesh.uk/) - Scottish community tools (also at [meshcore.scotmesh.net](https://meshcore.scotmesh.net/) and [scotmesh.mm7roq.compute.oarc.uk](https://scotmesh.mm7roq.compute.oarc.uk/)).

#### United States

- [Austin Mesh](https://www.austinmesh.org/)
- [Bay Area MeshCore](https://bayareameshcore.org/)
- [Boston Mesh](https://bostonme.sh/) - [Discord](https://discord.gg/MUVASVEEES)
- [CascadiaMesh](https://cascadiamesh.org) - [Discord](https://discord.gg/m9yarB3p2E)
- [Chicagoland Mesh](https://chicagolandmesh.org/) - MeshCore, Meshtastic and Reticulum; [Discord](https://chimesh.org/discord)
- [Colorado MeshCore](https://meshcore.coloradomesh.org/)
- [CT Mesh](https://ctmesh.org/) - [Discord](https://discord.gg/m4F328as3K)
- [Denver MeshCore](https://denvermc.com/)
- [Eastern US MeshCore](https://eastme.sh/)
- [Florida Mesh](https://areyoumeshingwith.us/) - Run by amateur radio operators.
- [Florida MeshCore](https://mc.flmesh.us/)
- [Gulf Coast Mesh](https://gulfcoastmesh.org) - Louisiana and US Gulf Coast.
- [Idaho Mesh](https://idahomesh.org) - Treasure Valley.
- [Inland NW Mesh](https://inlandnwmesh.org/) - Spokane, Coeur d'Alene, the Palouse, Lewiston/Clarkston; [Discord](https://discord.gg/VzFcvSxxyr)
- [Kentucky Mesh](https://mesh-ky.org/) - Also covers Meshtastic.
- [Lehigh Valley Mesh](https://lvmesh.com/) - Eastern Pennsylvania and New Jersey; [Discord](https://discord.lvmesh.com/)
- [Long Island Mesh](https://limesh.org/) - MeshCore and Meshtastic.
- [Madison Mesh](https://madmesh.net/) - Madison, Wisconsin.
- [Mesh America](https://meshamerica.com/) - Guides, wiki and network design articles.
- [MeshCore Lexington](https://meshcorelexington.com/)
- [MeshCore TX](https://meshcoretx.net/) - Texas radio preset and repeater naming standard.
- [MeshNY](https://nyme.sh/) - New York City.
- [MeshTexas](https://meshtexas.net/) - Statewide, shared MQTT broker.
- [Michigan Mesh Network](https://michmesh.com/) - Statewide; Meshtastic, MeshCore, Reticulum. [Discord](https://discord.gg/3A5RREcBcc) / [Signal](https://signal.group/#CjQKIG5-o6UUXvto66c1wN4fbinuguy614cJtRPmMxUA6JWyEhBKp6Q70OkA2MpcjsBYU1r9)
- [Missouri Mesh](https://missourimesh.org/) - Also covers Meshtastic; [Discord](https://missourimesh.org/discord)
- [Mountain West Mesh](https://mwmesh.com/) - Utah, Idaho, Wyoming.
- [MSP Mesh](https://mspmesh.org/) - Minneapolis-Saint Paul and Greater Minnesota.
- [Nebraska Mesh](https://www.nebraskamesh.net/)
- [Nevada Mesh](https://nvme.sh/) - Carson City, Reno, northern Nevada.
- [New England Mesh](https://nhmesh.com/) - CT, MA, NH and ME.
- [NodakMesh](https://nodakmesh.org/) - North Dakota; wiki and guides.
- [NTX Mesh](https://ntxmesh.com/) - Dallas-Fort Worth and greater North Texas; [Discord](https://discord.gg/nGeQ8cbSM3)
- [Pioneer Valley Mesh](https://pvmesh.org/) - Western Massachusetts.
- [Puget Mesh](https://pugetmesh.org/) - Puget Sound region.
- [RDUMesh](https://rdumesh.org/) - Raleigh, Durham, Chapel Hill.
- [RegionMesh](https://www.regionmesh.com/) - National hub with regional guides.
- [Southern California MeshCore](https://socalmesh.org/) - LA area; public CoreScope instance.
- [Spokane Mesh](https://www.spokanemesh.net/) - [Discord](https://discord.gg/VzFcvSxxyr)
- [STMesh](https://www.stmesh.net/) - New York Southern Tier.
- [TennMesh](https://tennmesh.com/) - Tennessee.
- [Upstate Mesh](https://www.upst8me.sh/) - New York Capital District.
- [West Coast Mesh](https://www.wcmesh.com/) - [Discord](https://discord.gg/wcmesh)
- [WNY MeshCore](https://wnymeshcore.org/) - Western New York.
