> [![Awesome list badge](https://awesome.re/badge.svg)](https://awesome.re) list of
 MeshCore resources. [Pull requests welcome!](https://github.com/samuk/awesome-meshcore)

MeshCore is a multi-platform system for enabling secure text based
communications utilising LoRa radio hardware. It can be used for off-grid
communication, emergency response & disaster recovery, outdoor activities and IoT
sensor networks.

## Contents

| Section | Subsections |
| :--- | :--- |
| [Official Resources](#official-resources) | [Social Media](#social-media) |
| [Communities](#communities) | [Africa](#africa) · [Asia](#asia) · [Europe](#europe) · [North America](#north-america) · [Oceania](#oceania) · [South America](#south-america) |
| [Hardware](#hardware) | [Pre-built Devices](#pre-built-devices) · [Supported Devices](#supported-devices) · [DIY Builds](#diy-builds) · [Enclosures and Mounts](#enclosures-and-mounts) |
| [Clients](#clients) | [Cross-Platform](#cross-platform) · [Android](#android) · [iOS and Apple](#ios-and-apple) · [Desktop](#desktop) · [Web](#web) · [Terminal](#terminal) · [Other Platforms](#other-platforms) |
| [Firmware and Flashing](#firmware-and-flashing) | [Custom Firmware](#custom-firmware) · [Flashing and Updating](#flashing-and-updating) |
| [Maps and Diagnostics](#maps-and-diagnostics) | [Maps](#maps) · [Diagnostics and Dashboards](#diagnostics-and-dashboards) · [RF Planning](#rf-planning) |
| [Utilities](#utilities) | [Libraries and SDKs](#libraries-and-sdks) · [Integrations and Bots](#integrations-and-bots) · [Self-Hosted Dashboards](#self-hosted-dashboards) · [Packet Analysis](#packet-analysis) · [Miscellaneous](#miscellaneous) |
| [Guides and Learning](#guides-and-learning) | |

> Apps and firmware marked 🔒 are closed source.

---

##  Resources

- [MeshCore.io](https://meshcore.io/) - The official homepage.
- [Documentation](https://docs.meshcore.io/) - Official docs.
- [Blog](https://blog.meshcore.io/) - Official announcements and releases.
- [MeshCore Web Flasher](https://flasher.meshcore.io/) - Official browser-based firmware flasher for supported devices.
- [MeshCore Map](https://map.meshcore.io/) - Official network map.
- [The FAQ](https://github.com/meshcore-dev/MeshCore/blob/main/docs/faq.md) - Official answers on setup, roles and radio settings.
- [Firmware repository](https://github.com/meshcore-dev/MeshCore) MIT licensed firmware. 
- [Current state of MeshCore encryption](https://github.com/meshcore-dev/MeshCore/issues/259) - Discussion thread on the project's encryption roadmap.
- [Repeater/Room Config](https://config.meshcore.io/) - Official browser-based USB configuration tool for repeaters and room servers.

### Social Media

- [Discord](https://meshcore.gg) 
- [Reddit r/meshcore](https://www.reddit.com/r/meshcore/) 
- [Facebook group](https://www.facebook.com/groups/meshcore)
- [Mastodon](https://mastodon.social/@meshcore)
- [X](https://x.com/mesh_core) 

## Communites

[Africa](#africa) 

[Asia](#asia) 

[Europe](#europe) 

[North America](#north-america) 

[Oceania](#oceania) 

[South America](#south-america) 

## Hardware

### Pre-built Devices

Sold with MeshCore firmware pre-installed, or with MeshCore selectable at order. For Europe get 868Mhz for N.America 915Mhz

| Product | Price (USD) | Description |
| :--- | :--- | :--- |
| [Seeed Wio Tracker L1 Pro for MeshCore](https://www.seeedstudio.com/Wio-Tracker-L1-Pro-for-Meshcore-p-6717.html) | ~$47.90 | Handheld with GPS, OLED display and battery. |
| [RAK WisMesh Tag (Atlavox)](https://atlavox.com/products/wismesh-tag-meshtastic-meshcore-radio) | ~$49.99 | IP66 GPS tracker; choose the MeshCore variant when ordering. |
| [LilyGo T-Deck Plus](https://lilygo.cc/products/t-deck-plus-1?variant=51618501951669) | ~$70.99 | Handheld with keyboard, 2.8" LCD, GPS and SX1262 radio. |
| [Elecrow ThinkNode M9](https://www.elecrow.com/thinknode-m9-meshcore-communication-terminal-with-full-keyboard-2-4inch-lcd-esp32-s3-lr1110-gps-2300mah.html) | ~$74.90 | Standalone communicator with QWERTY keyboard, colour LCD and GPS. |
| [LilyGo T-LoRa Pager MeshCore](https://lilygo.cc/products/t-lora-pager-meshcore) | ~$87.35 | Pocket pager with keyboard, display and LR1121 radio. |
| [SenseCAP Solar Node P1 Pro for MeshCore](https://www.seeedstudio.com/SenseCAP-Solar-Node-P1-Pro-for-Meshcore-p-6741.html) | ~$93.90 | Solar-powered outdoor repeater with GPS. |
| [Seeed MeshCore Starter Kit](https://www.seeedstudio.com/MeshCore-Starter-Kit-Ready-to-Use-Off-Grid-Instant-Reliable-Communication.html) | from ~$141+  | Bundle of a repeater and client nodes ready to deploy. |

Prices last checked 9 October 2026.

### Supported Devices

Compatibility references; check these before buying a board.

| Resource | Description |
| :--- | :--- |
| [MeshCore Europe devices](https://meshcoreeurope.org/en/devices/) | Multilingual device directory with setup guides. |
| [mesh-sn.de firmware matrix](https://mesh-sn.de/en/devices/matrix) | Per-device matrix of which MeshCore firmware builds are available. |
| [Mesh America supported hardware](https://wiki.meshamerica.com/books/meshcore/page/supported-hardware-for-meshcore) | Community list of compatible boards and chipsets. |
| [LocalMesh UK devices](https://localmesh.co.uk/devices/) | Device guides for the UK emergency network. |

### DIY Builds

Open designs with published files (PCB, BOM, STL or detailed build guide).

| Project | Description |
| :--- | :--- |
| [LoRaHarvesterBox](https://github.com/h0lad/LoRaHarvesterBox) ![GitHub Repo stars](https://img.shields.io/github/stars/h0lad/LoRaHarvesterBox?style=social) | STM32WLE5CC LoRa base board with a BQ25570 energy harvester for MeshCore or Meshtastic nodes. |
| [SolarMeshtasticNodeMini](https://github.com/h0lad/SolarMeshtasticNodeMini) ![GitHub Repo stars](https://img.shields.io/github/stars/h0lad/SolarMeshtasticNodeMini?style=social) | Miniaturised 37×47mm solar node compatible with MeshCore and Meshtastic. |
| [LoRaMeshNodes](https://github.com/hotwolf/LoRaMeshNodes) ![GitHub Repo stars](https://img.shields.io/github/stars/hotwolf/LoRaMeshNodes?style=social) | Mobile and solar nodes with OpenSCAD enclosures, STL files and BOMs. |
| [bardolf MeshCore Repeater](https://github.com/bardolf/meshcore-repeater) ![GitHub Repo stars](https://img.shields.io/github/stars/bardolf/meshcore-repeater?style=social) | Solar repeater with FreeCAD enclosure, STL files and full BOM. |
| [915 MHz Mesh Antenna](https://github.com/ellisgl/915-mesh-antenna) ![GitHub Repo stars](https://img.shields.io/github/stars/ellisgl/915-mesh-antenna?style=social) | Stacked collinear antenna with simulation files and build dimensions. |
| [MeshCore E22P Repeater](https://github.com/Sukecz/MeshCore-E22P-Repeater) ![GitHub Repo stars](https://img.shields.io/github/stars/Sukecz/MeshCore-E22P-Repeater?style=social) | XIAO ESP32-S3 repeater with an Ebyte E22P module, wiring and firmware. |
| [XIAO S3 Dual-Radio Repeater](https://github.com/bouyous/meshcore-xiao-s3-dual-radio-repeater) ![GitHub Repo stars](https://img.shields.io/github/stars/bouyous/meshcore-xiao-s3-dual-radio-repeater?style=social) | Two-radio summit repeater with assembly guide and field test reports. |
| [RePeter](https://github.com/robrec/MeshCoreRepeater-RePeter) ![GitHub Repo stars](https://img.shields.io/github/stars/robrec/MeshCoreRepeater-RePeter?style=social) | Bremen repeater board with Gerbers, schematics, BOM and STEP model. |
| [NodakMesh solar repeater build](https://nodakmesh.org/blog/meshcore-solar-repeater-build) | Parts list, solar sizing, weatherproofing and configuration walkthrough. |

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

## Clients

> Grouped by platform. Apps marked 🔒 are closed source.

### Cross-Platform

| Project Name | Description |
| :--- | :--- |
| [Meshcore Open](https://github.com/zjs81/meshcore-open) ![GitHub Repo stars](https://img.shields.io/github/stars/zjs81/meshcore-open?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/zjs81/meshcore-open) | Open-source Flutter client for mobile and desktop (Android, iOS, GNU/Linux, Windows, macOS). |
| [Meshcore SAR](https://github.com/dz0ny/meshcore-sar) ![GitHub Repo stars](https://img.shields.io/github/stars/dz0ny/meshcore-sar?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/dz0ny/meshcore-sar) | Offline-first search-and-rescue app: messaging, voice, images, maps and live location context in one app. (AI code) |
| [MeshCore TEAM](https://github.com/tmacinc/MeshCore-TEAM) ![GitHub Repo stars](https://img.shields.io/github/stars/tmacinc/MeshCore-TEAM?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/tmacinc/MeshCore-TEAM) | Source of the cross-platform MeshCore TEAM companion app: team-oriented location tracking, messaging, contacts, channels and maps on stock firmware. |
| [Offband MeshCore](https://github.com/OffbandMesh/meshcore-client) ![GitHub Repo stars](https://img.shields.io/github/stars/OffbandMesh/meshcore-client?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/OffbandMesh/meshcore-client) | Cross-platform client with direct and channel chat. |
| [SigurdOS Client](https://github.com/hermes-gadget/SigurdOS-client) ![GitHub Repo stars](https://img.shields.io/github/stars/hermes-gadget/SigurdOS-client?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/hermes-gadget/SigurdOS-client) | Companion app for GNU/Linux, Android, iOS, Windows, macOS, forked from Meshcore Open for "SigurdOS T-Deck" firmware. |
| [MCO Advanced](https://github.com/HDDen/meshcore-open) ![GitHub Repo stars](https://img.shields.io/github/stars/HDDen/meshcore-open?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/HDDen/meshcore-open) | MeshCore Open fork with one-packet lossless image sending (MCOimg), built-in wardriving and text compression. |
| [Official app](https://files.liamcottle.net/MeshCore/) 🔒 | Proprietary companion app, also on Google Play and the App Store. |
| [Nelos](https://nelos.app/) 🔒 | iOS/Android app for group messaging and tracking people, pets and belongings, with downloadable offline maps. |
| [KIEKR](https://kiekr.app/) 🔒 | iOS and Android community toolbox app; can display incoming message scope, upload data to analysers, unlimited contacts. |

### Android

| Project Name | Description |
| :--- | :--- |
| [Meshcore Open](https://github.com/zjs81/meshcore-open) ![GitHub Repo stars](https://img.shields.io/github/stars/zjs81/meshcore-open?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/zjs81/meshcore-open) | Open-source [Android client on Play](https://play.google.com/store/apps/details?id=com.meshcore.meshcore_open) |
| [Meshcore-Wardrive-Android](https://github.com/mintylinux/Meshcore-Wardrive-Android) ![GitHub Repo stars](https://img.shields.io/github/stars/mintylinux/Meshcore-Wardrive-Android?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/mintylinux/Meshcore-Wardrive-Android) | Flutter wardriving and mapping app. |
| [Tactical Emergency Area Messaging](https://github.com/tmacinc/meshcore-team-alpha) ![GitHub Repo stars](https://img.shields.io/github/stars/tmacinc/meshcore-team-alpha?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/tmacinc/meshcore-team-alpha) | Android application for position tracking and messaging. |
| [Peers](https://github.com/xAlisher/peers) ![GitHub Repo stars](https://img.shields.io/github/stars/xAlisher/peers?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/xAlisher/peers) | Privacy-focused Android messenger routing over Logos, MeshCore and Bluetooth mesh. |
| [Yours](https://github.com/STCisGOOD/yours-x-lunarcore) ![GitHub Repo stars](https://img.shields.io/github/stars/STCisGOOD/yours-x-lunarcore?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/STCisGOOD/yours-x-lunarcore) | Android encrypted P2P messaging client for LunarCore firmware, with onion-routing experiments. |
| [meshtrax](https://github.com/venamartin/meshtrax) ![GitHub Repo stars](https://img.shields.io/github/stars/venamartin/meshtrax?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/venamartin/meshtrax) | Flutter Android client with mapping and messaging. |
| [meshcore-mobile-app](https://github.com/thatSFguy/meshcore-mobile-app) ![GitHub Repo stars](https://img.shields.io/github/stars/thatSFguy/meshcore-mobile-app?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/thatSFguy/meshcore-mobile-app) | Hardened Android client, no Google Play Services required. |
| [MeshCore-TEAM](https://play.google.com/store/apps/details?id=com.meshcore.team) 🔒 | Android client focused on group operations (Play Store build of [MeshCore TEAM](https://github.com/tmacinc/MeshCore-TEAM)). |
| [meshGO!](https://play.google.com/store/apps/details?id=com.meshcore.meshgo) 🔒 | Android off-grid messaging client. |
| [MeshMapper](https://play.google.com/store/apps/details?id=net.meshmapper.app) 🔒 | Android coverage mapping and wardriving app. |

### iOS and Apple

| Project Name | Description |
| :--- | :--- |
| [MeshCore One](https://github.com/Avi0n/MeshCoreOne) ![GitHub Repo stars](https://img.shields.io/github/stars/Avi0n/MeshCoreOne?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Avi0n/MeshCoreOne) | Native Swift client for iOS, iPadOS and macOS. (AI code) |
| [PommeCore](https://github.com/mbedworth/PommeCore) ![GitHub Repo stars](https://img.shields.io/github/stars/mbedworth/PommeCore?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/mbedworth/PommeCore) | SwiftUI companion app for Apple platforms. |

### Desktop

| Project Name | Description |
| :--- | :--- |
| [mesh-client](https://github.com/Colorado-Mesh/mesh-client) ![GitHub Repo stars](https://img.shields.io/github/stars/Colorado-Mesh/mesh-client?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Colorado-Mesh/mesh-client) | Electron desktop client for MeshCore, Meshtastic and Reticulum. |
| [meshy](https://codeberg.org/sesivany/meshy) 68 stars<br>Oct 26 | GTK4/libadwaita client for Linux and macOS, aiming for the best Linux experience. |
| [MeshApp](https://github.com/smikme/meshapp) ![GitHub Repo stars](https://img.shields.io/github/stars/smikme/meshapp?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/smikme/meshapp) | Desktop client for MeshCore and Meshtastic with telemetry views. |
| [MeshCore gui](https://github.com/pe1hvh/meshcore-gui) ![GitHub Repo stars](https://img.shields.io/github/stars/pe1hvh/meshcore-gui?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/pe1hvh/meshcore-gui) | Native desktop client over BLE, no firmware changes required. |
| [PyMeshCoreGUI](https://github.com/bliksemlabs/PyMeshCoreGUI) ![GitHub Repo stars](https://img.shields.io/github/stars/bliksemlabs/PyMeshCoreGUI?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/bliksemlabs/PyMeshCoreGUI) | Qt6 and Python desktop client. |
| [mcIRC](https://github.com/bclml/mcIRC) ![GitHub Repo stars](https://img.shields.io/github/stars/bclml/mcIRC?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/bclml/mcIRC) | IRC-style desktop client (Windows; Linux and macOS experimental) with several nodes at once, bots and addons, and a firmware builder for companions, repeaters, room servers and observers. |
| [MeshCore Insights](https://github.com/BomBefok/MeshcoreInsights) ![GitHub Repo stars](https://img.shields.io/github/stars/BomBefok/MeshcoreInsights?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/BomBefok/MeshcoreInsights) | Desktop dashboard with live maps, telemetry analysis and remote node management. |
| [MeshCoreQt](https://github.com/zhrkvl/MeshCoreQt) ![GitHub Repo stars](https://img.shields.io/github/stars/zhrkvl/MeshCoreQt?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/zhrkvl/MeshCoreQt) | Qt desktop client. |
| [QMeshcoreApp](https://github.com/FelixvdDonk/QMeshcoreApp) ![GitHub Repo stars](https://img.shields.io/github/stars/FelixvdDonk/QMeshcoreApp?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/FelixvdDonk/QMeshcoreApp) | Qt6/QML desktop companion with BLE/serial, map and RX log. |
| [meshcore-bin (AUR)](https://aur.archlinux.org/packages/meshcore-bin) 🔒 | Arch Linux package of the official app. |

### Web

| Project Name | Description |
| :--- | :--- |
| [MC-WebUI](https://github.com/MarekWo/mc-webui) ![GitHub Repo stars](https://img.shields.io/github/stars/MarekWo/mc-webui?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/MarekWo/mc-webui) | WebUI for meshcore-cli. (AI code) |
| [Mycelium](https://github.com/WattleFoxxo/Mycelium) ![GitHub Repo stars](https://img.shields.io/github/stars/WattleFoxxo/Mycelium?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/WattleFoxxo/Mycelium) | Browser client for messaging over serial or BLE. |
| [MeshCorium](https://github.com/PEG4TRON/MeshCorium) ![GitHub Repo stars](https://img.shields.io/github/stars/PEG4TRON/MeshCorium?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/PEG4TRON/MeshCorium) | Self-hosted client with a local web interface and hybrid contact system. |
| [meshcore-webui](https://github.com/adradr/meshcore-webui) ![GitHub Repo stars](https://img.shields.io/github/stars/adradr/meshcore-webui?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/adradr/meshcore-webui) | Web UI for managing devices and chatting on the mesh. |
| [MeshCore Companion](https://github.com/edleeman17/meshcore-companion) ![GitHub Repo stars](https://img.shields.io/github/stars/edleeman17/meshcore-companion?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/edleeman17/meshcore-companion) | Self-hosted web client with signal diagnostics, an antenna placement mode, and signed channel posts to catch name spoofing. |
| [meshcore-web (aXistem)](https://github.com/aXistem-dev/meshcore-web) ![GitHub Repo stars](https://img.shields.io/github/stars/aXistem-dev/meshcore-web?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/aXistem-dev/meshcore-web) | Docker-ready browser build of the companion app over BLE or USB; image `ghcr.io/axistem-dev/meshcore-web`. |
| [Official web app](https://app.meshcore.io/) 🔒 | Browser build of the official companion app. |

### Terminal

| Project Name | Description |
| :--- | :--- |
| [meshtui](https://github.com/ekollof/meshtui) ![GitHub Repo stars](https://img.shields.io/github/stars/ekollof/meshtui?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/ekollof/meshtui) | Textual terminal client with delivery tracking and device management. |
| [MeshTerm](https://meshterm.net/) ![GitHub Repo stars](https://img.shields.io/github/stars/jpmartineau/MeshTerm?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/jpmartineau/MeshTerm) | Cross-platform TUI client over USB, BLE or TCP with maps, traceroute and message-path views. |
| [tui-meshcore](https://github.com/guax/tui-meshcore) ![GitHub Repo stars](https://img.shields.io/github/stars/guax/tui-meshcore?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/guax/tui-meshcore) | Terminal chat client with persistent history and regional presets. |
| [QTC](https://github.com/initsixdev/QTC) ![GitHub Repo stars](https://img.shields.io/github/stars/initsixdev/QTC?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/initsixdev/QTC) | Old-school terminal client for Linux and macOS. |
| [MeshChaTUI](https://github.com/g-d-j-evans/MeschaTUI) ![GitHub Repo stars](https://img.shields.io/github/stars/g-d-j-evans/MeschaTUI?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/g-d-j-evans/MeschaTUI) | Textual terminal client for Linux with delivery confirmation over serial or BLE. |
| [Remote Terminal for MeshCore](https://github.com/MichTronics/Remote-Terminal-for-MeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/MichTronics/Remote-Terminal-for-MeshCore?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/MichTronics/Remote-Terminal-for-MeshCore) | Remote terminal for repeaters with packet capture and MQTT. |

### Other Platforms

| Project Name | Description |
| :--- | :--- |
| [Roadstr](https://github.com/jooray/roadstr) ![GitHub Repo stars](https://img.shields.io/github/stars/jooray/roadstr?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/jooray/roadstr) | Decentralized road-event reporting over signed Nostr events with MeshCore as transport — "Waze without the centralized tracking." |
| [Sestriere](https://github.com/atomozero/Sestriere) ![GitHub Repo stars](https://img.shields.io/github/stars/atomozero/Sestriere?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/atomozero/Sestriere) | Native Haiku OS client with maps, packet analysis and repeater administration. (AI code) |
| [PicoMeshCore](https://github.com/Vigoleis912/PicoMeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/Vigoleis912/PicoMeshCore?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Vigoleis912/PicoMeshCore) | MMBasic companion client for the Raspberry Pi Pico (PicoMite) over UART. |
| [MeshCore64](https://github.com/swannman/meshcore64) ![GitHub Repo stars](https://img.shields.io/github/stars/swannman/meshcore64?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/swannman/meshcore64) | Commodore 64 chat client over a SwiftLink-compatible serial cartridge. |

## Firmware and Flashing

### Custom Firmware
> Firmware marked 🔒 is closed source.

| Project Name | Description |
| :--- | :--- |
| [Trail Mate](https://github.com/vicliu624/trail-mate) ![GitHub Repo stars](https://img.shields.io/github/stars/vicliu624/trail-mate?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/vicliu624/trail-mate) | **LilyGO T-LoRa-Pager, T-Deck** (primary); M5Stack Tab5, T-Display P4 (bring-up); T-Watch S3 (experimental). Offline-first navigation with offline GPS maps, Meshtastic + MeshCore messaging, SSTV receiver, FSK+Codec2 walkie-talkie, ESP-NOW team mode, Sub-GHz sweep. |
| [EasySkyMesh](https://github.com/IoTThinks/EasySkyMesh) ![GitHub Repo stars](https://img.shields.io/github/stars/IoTThinks/EasySkyMesh?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/IoTThinks/EasySkyMesh) | Power-saving fork for ultra-low-power repeater and sensor deployments. |
| [SolarOS](https://github.com/nilseuropa/solar_os) ![GitHub Repo stars](https://img.shields.io/github/stars/nilseuropa/solar_os?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/nilseuropa/solar_os) | ESP32 pocket-terminal OS with a MeshCore companion job over a local LoRa radio or a BLE-paired node. |
| [MeshCore Wio Tracker L1 Pro (sosprz)](https://github.com/sosprz/Meshcore-Wio-Tracker-L1-Pro) ![GitHub Repo stars](https://img.shields.io/github/stars/sosprz/Meshcore-Wio-Tracker-L1-Pro?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/sosprz/Meshcore-Wio-Tracker-L1-Pro) | **Seeed Studio Wio Tracker L1 Pro.** On-device companion UI with UF2 drag-and-drop and web flasher support. |
| [LunarCore](https://github.com/STCisGOOD/lunarcore) ![GitHub Repo stars](https://img.shields.io/github/stars/STCisGOOD/lunarcore?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/STCisGOOD/lunarcore) | **Heltec WiFi LoRa 32 V3 (ESP32-S3 + SX1262).** Multi-protocol Rust firmware combining MeshCore, Meshtastic and RNode/KISS (Reticulum) on one device. |
| [ZephCore](https://github.com/liquidraver/ZephCore) ![GitHub Repo stars](https://img.shields.io/github/stars/liquidraver/ZephCore?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/liquidraver/ZephCore) | **nRF52840:** Wio Tracker L1, Seeed T1000-E, RAK4631, RAK WisMesh Tag, ThinkNode M1, Ikoka Nano 30dBm. **ESP32:** XIAO ESP32-C3/C6, Station G2, LilyGo TLoRa C6. **Other:** XIAO nRF54L15, XIAO MG24. Port from Arduino to Zephyr RTOS: WFI sleep, adaptive contention window, CAD-based RX duty cycling, UF2/DFU. |
| [Wadamesh](https://www.wadamesh.com/) ([GitHub repository](https://github.com/ALLFATHER-BV/wadamesh)) ![GitHub Repo stars](https://img.shields.io/github/stars/ALLFATHER-BV/wadamesh?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/ALLFATHER-BV/wadamesh) | **LilyGo:** T-Deck, T-Deck Max, T-Deck Pro (V1.0/V1.1), T-LoRa Pager (SX1262/LR1121), T-Display P4 (AMOLED/LCD, SX1262/LR2021). **Heltec:** V4 TFT, V4-R8. **Other:** RAK WisMesh Tap V2, ThinkNode M9, Seeed Wio Tracker L2, Elecrow CrowPanel Advance 3.5, Attaky Core. Standalone LVGL touch UI: on-device chat, channels, rooms, contacts, live map, OTA updates, no phone required. Split out of Meshcomod. |
| [MeshCore Cardputer ADV (Stachugit)](https://github.com/Stachugit/MeshCore-Cardputer-ADV) ![GitHub Repo stars](https://img.shields.io/github/stars/Stachugit/MeshCore-Cardputer-ADV?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Stachugit/MeshCore-Cardputer-ADV) | **M5Stack Cardputer-ADV** with Cap LoRa868 or DX-LR30-900M22SP. Enhanced TFT UI with chat bubbles, 18 colour themes, notification popups, Bluetooth pairing. |
| [MeshCoreTerm (Dabeani)](https://github.com/dabeani/meshcoreterm) ![GitHub Repo stars](https://img.shields.io/github/stars/dabeani/meshcoreterm?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/dabeani/meshcoreterm) | **LilyGO T-Deck, T-Deck Plus, Seeed Studio SenseCap Indicator (TFT/D1Pro).** Retro-themed, touch-first UI: tabbed interface (Contacts, Channels, Map, Mgmt), slippy tile map, D-pad/trackball support, RSSI/SNR display, telemetry. |
| [MeshCore mishmesh](https://github.com/burakcan/MeshCore-mishmesh) ![GitHub Repo stars](https://img.shields.io/github/stars/burakcan/MeshCore-mishmesh?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/burakcan/MeshCore-mishmesh) | On-device UI making a companion radio usable without a paired phone. |
| [Meshcomod](https://meshcomod.com/) ([GitHub repository](https://github.com/ALLFATHER-BV/meshcomod)) ![GitHub Repo stars](https://img.shields.io/github/stars/ALLFATHER-BV/meshcomod?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/ALLFATHER-BV/meshcomod) | **Heltec and Seeed LoRa devices.** Companion firmware offering USB + Bluetooth + TCP simultaneously (phone app, web client or Home Assistant). |
| [MeshCore Solo](https://github.com/MarekZegare4/MeshCore-Solo) ![GitHub Repo stars](https://img.shields.io/github/stars/MarekZegare4/MeshCore-Solo?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/MarekZegare4/MeshCore-Solo) | **Seeed Studio Wio Tracker L1 (OLED and eInk), GAT562 30S Mesh Kit.** Standalone firmware based on the official companion firmware, adding offline GPS navigation and GPX export. |
| [MeshCore Low-Power](https://github.com/dt267/MeshCore-Low-Power-Firmware-For-Heltec-V3-V4) ![GitHub Repo stars](https://img.shields.io/github/stars/dt267/MeshCore-Low-Power-Firmware-For-Heltec-V3-V4?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/dt267/MeshCore-Low-Power-Firmware-For-Heltec-V3-V4) | **Heltec V3/V4.** Deep-sleep builds with BLE, USB and WiFi in one image. |
| [MeshCore Cardputer ADV (sosprz)](https://github.com/sosprz/meshcore-cardputer-adv) ![GitHub Repo stars](https://img.shields.io/github/stars/sosprz/meshcore-cardputer-adv?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/sosprz/meshcore-cardputer-adv) | **M5Stack Cardputer-ADV (ESP32-S3), Cap LoRa868.** Specialized UI; flashable via M5Burner, ESP flasher tools, or web flasher. |
| [MeshPunk](https://github.com/PhilMo6/meshpunk) ![GitHub Repo stars](https://img.shields.io/github/stars/PhilMo6/meshpunk?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/PhilMo6/meshpunk) | **LilyGo T-Deck.** LVGL and Lua handheld firmware. |
| [MeshCoreTel](https://github.com/VBart/MeshCoreTel-firmware) ![GitHub Repo stars](https://img.shields.io/github/stars/VBart/MeshCoreTel-firmware?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/VBart/MeshCoreTel-firmware) | Repeater fork of EastMesh with WiFi, HTTPS API, web panel and MQTT. |
| [MCLite](https://github.com/laserir/MCLite) ![GitHub Repo stars](https://img.shields.io/github/stars/laserir/MCLite?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/laserir/MCLite) | **LilyGO T-Deck Plus.** Simplified firmware for non-technical users: zero-config via SD card JSON, LVGL touch UI, DMs and channels, SOS, GPS sharing, multi-language, PIN lock, SD message history. |
| [Meck](https://github.com/pelgraine/Meck) ![GitHub Repo stars](https://img.shields.io/github/stars/pelgraine/Meck?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/pelgraine/Meck) | **LilyGO T-Deck Pro, T-Deck Max, T5 E-Paper S3 Pro.** BLE and WiFi companion fork; early-stage, repeater and USB firmware still in development. |
| [FieldMesh](https://github.com/TogeriX-hub/FieldMesh) ![GitHub Repo stars](https://img.shields.io/github/stars/TogeriX-hub/FieldMesh?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/TogeriX-hub/FieldMesh) | **Elecrow ThinkNode M1, Seeed Wio Tracker L1** (tested). Outdoor-focused fork for festivals, hiking and off-grid events: automatic GPS advertising, Haversine tracking page, one-press Off-Grid mode, SOS alerts. |
| [EastMesh](https://github.com/xJARiD/MeshCore-EastMesh) ![GitHub Repo stars](https://img.shields.io/github/stars/xJARiD/MeshCore-EastMesh?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/xJARiD/MeshCore-EastMesh) | MQTT repeater and WiFi companion builds with prebuilt releases. |
| [SigurdOS T-Deck](https://github.com/hermes-gadget/SigurdOS-tdeck) ![GitHub Repo stars](https://img.shields.io/github/stars/hermes-gadget/SigurdOS-tdeck?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/hermes-gadget/SigurdOS-tdeck) | Launcher-style touch UI for the T-Deck with maps and over-the-air updates. GPL-3.0-or-later. |
| [MeshCore Cardputer-ADV (MultiMote)](https://github.com/MultiMote/meshcore-cardputer-adv) ![GitHub Repo stars](https://img.shields.io/github/stars/MultiMote/meshcore-cardputer-adv?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/MultiMote/meshcore-cardputer-adv) | **M5Stack Cardputer Adv with Cap LoRa-1262.** Fork for this module combination. |
| [Saitama](https://github.com/868meshbot/Saitama) ![GitHub Repo stars](https://img.shields.io/github/stars/868meshbot/Saitama?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/868meshbot/Saitama) | **LilyGo T-Deck, T-Deck Plus.** Standalone firmware for LoRa mesh devices, built on MeshCore. |
| [Offband Mesh](https://github.com/OffbandMesh/meshcore-firmware) ![GitHub Repo stars](https://img.shields.io/github/stars/OffbandMesh/meshcore-firmware?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/OffbandMesh/meshcore-firmware) | Cross-role firmware enhancements and optimisation. |
| [CubeCell MeshCore](https://github.com/atomozero/CubeCellMeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/atomozero/CubeCellMeshCore?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/atomozero/CubeCellMeshCore) | **Heltec CubeCell HTCC-AB01, AB02, AC01** (ASR6501 + SX1262). Repeater-only firmware optimised for solar deployments: store-and-forward mailbox, mesh health monitor, remote CLI, adaptive TX power, deep sleep (~3.5 µA). |
| [Meck-P4](https://github.com/pelgraine/Meck-P4) ![GitHub Repo stars](https://img.shields.io/github/stars/pelgraine/Meck-P4?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/pelgraine/Meck-P4) | **LilyGo T-Display P4 (ESP32-P4).** Port of Meck to the P4 platform. |
| [MeshCore T-beam-1W](https://github.com/mintylinux/Meshcore-T-beam-1W-Firmware) ![GitHub Repo stars](https://img.shields.io/github/stars/mintylinux/Meshcore-T-beam-1W-Firmware?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/mintylinux/Meshcore-T-beam-1W-Firmware) | **LilyGO T-Beam 1 Watt** (SX1262, ESP32). Ported firmware with device-specific fixes for battery, boot loops and the 1W PA; includes a web flasher. |
| [MC-T5-Pro](https://github.com/dz0ny/meshcore-t5-epaper-s3-pro) ![GitHub Repo stars](https://img.shields.io/github/stars/dz0ny/meshcore-t5-epaper-s3-pro?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/dz0ny/meshcore-t5-epaper-s3-pro) | **LilyGo T5 ePaper S3 Pro.** A paper-like handheld MeshCore communicator. |
| [MeshCore PaperUI](https://github.com/dz0ny/meshcore-paperui) ![GitHub Repo stars](https://img.shields.io/github/stars/dz0ny/meshcore-paperui?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/dz0ny/meshcore-paperui) | E-paper handheld firmware with standalone messaging, GPS and maps. |
| [MeshCore Filter Firmware](https://github.com/jhuebert/MeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/jhuebert/MeshCore?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/jhuebert/MeshCore) | **All MeshCore repeater targets** (Heltec V3/V4, CT-62, Wireless Tracker; Station G2/G3; RAK4631/3401; SenseCap Solar; XIAO ESP32-S3/nRF52; T1000-E; Generic E22 SX1262). Remotely configurable drop/forward rules by channel, sender, text, packet type, hops, region and signal strength over the repeater CLI; per-rule throttling, advert rate limiting, saved-airtime telemetry, battery voltage gate. Prebuilt firmware on Releases (filter-v* tags); guide in FILTER.md. |
| [Fennek](https://github.com/danst0/fennek) ![GitHub Repo stars](https://img.shields.io/github/stars/danst0/fennek?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/danst0/fennek) | **LilyGO T-Deck Pro.** Adds music, audiobooks and eBooks alongside mesh chat. |
| [MeshCoreNG](https://github.com/MichTronics/MeshCoreNG) ![GitHub Repo stars](https://img.shields.io/github/stars/MichTronics/MeshCoreNG?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/MichTronics/MeshCoreNG) | Dutch fork focused on smarter repeaters for larger, busier meshes. |
| [TapTap Firmware (T1000-E)](https://github.com/mtoolstec/TapTapFW) ![GitHub Repo stars](https://img.shields.io/github/stars/mtoolstec/TapTapFW?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/mtoolstec/TapTapFW) | **Seeed Studio T1000-E, RAK WisMesh Tag.** Headless button-interaction firmware: canned messages, Morse entry, GPS toggle, RTTTL/CW buzzer alerts. |
| [BlackJackOS](https://github.com/Robert-Proaps/BlackJackOS-BJOS-) ![GitHub Repo stars](https://img.shields.io/github/stars/Robert-Proaps/BlackJackOS-BJOS-?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Robert-Proaps/BlackJackOS-BJOS-) | **LilyGo T-Deck, T-Deck Plus.** Portable toolbox and platform for building apps and functionality, with an application-oriented standalone interface. |
| [chiyocore](https://github.com/kore-signet/chiyocore) ![GitHub Repo stars](https://img.shields.io/github/stars/kore-signet/chiyocore?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/kore-signet/chiyocore) | **Generic ESP32 with SX1262/SX1276.** Experimental Rust reimplementation of MeshCore, alternative to the C++ Arduino implementation. |
| [MeshcoreGRID](https://github.com/Quark1980/MeshcoreGRID) ![GitHub Repo stars](https://img.shields.io/github/stars/Quark1980/MeshcoreGRID?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Quark1980/MeshcoreGRID) | **Heltec WiFi LoRa 32 V4 TFT** (ESP32-S3, FT6336 touchscreen). Touch-first UI with Messenger (DM + channel chat, ACK tracking), Discover (advert browser), Radio/BLE/Settings/Power apps, pinch-to-zoom Map. BETA. |
| [MeshCore TEAM enhanced firmware](https://github.com/tmacinc/MeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/tmacinc/MeshCore?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/tmacinc/MeshCore) | **Autonomous tracker custom firmware.** Layered on stock MeshCore, adding team-oriented GPS tracking, smart forwarding control and unattended autonomous operation. |
| [InkCore](https://codeberg.org/todd-herbert/InkCore) | AI-free BLE-companion firmware for small e-paper devices with configurable applets. Hosted on Codeberg, so no GitHub stars. |
| [MeshUltra](https://tdeck.ubnzeek.com/) 🔒 | **LilyGo T-Deck, T-Deck+.** Firmware for both devices. Closed source, so no repo to star. |

### Flashing and Updating
| Project Name | Description |
| :--- | :--- |
| [MeshFirmware](https://github.com/mikecarper/meshfirmware) ![GitHub Repo stars](https://img.shields.io/github/stars/mikecarper/meshfirmware?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/mikecarper/meshfirmware?label=last%20updated) | Interactive Windows and Linux scripts for selecting, flashing and compiling releases. |
| [Mesh Loader](https://github.com/eliahreeves/mesh-loader) ![GitHub Repo stars](https://img.shields.io/github/stars/eliahreeves/mesh-loader?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/eliahreeves/mesh-loader?label=last%20updated) | **Heltec WiFi LoRa 32 V3/V4** (other 8 MB+ flash ESP32 devices can be added). "Dual Boot" firmware switching between MeshCore and Meshtastic at boot via a 2-second button press, with isolated NVS/filesystem data per firmware. |
| [MeshCore Drone Updater](https://github.com/lucidnx/meshcore-drone-updater) ![GitHub Repo stars](https://img.shields.io/github/stars/lucidnx/meshcore-drone-updater?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/lucidnx/meshcore-drone-updater?label=last%20updated) | Raspberry Pi service for drive-by or drone-assisted DFU updates of physically unreachable nodes. |
| [MeshCore M5Burner UnitC6L](https://github.com/TheRealHaoLiu/MeshCore-M5Burner-UnitC6L) ![GitHub Repo stars](https://img.shields.io/github/stars/TheRealHaoLiu/MeshCore-M5Burner-UnitC6L?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/TheRealHaoLiu/MeshCore-M5Burner-UnitC6L?label=last%20updated) | Pre-built MeshCore firmware variants for the M5Stack Unit C6L via M5Burner. |
| [MeshCore OTA guide](https://github.com/Mraanderson/meshcore-ota) ![GitHub Repo stars](https://img.shields.io/github/stars/Mraanderson/meshcore-ota?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Mraanderson/meshcore-ota?label=last%20updated) | Step-by-step OTA firmware update guide for repeaters and room servers. |
| [Python Nordic Legacy DFU Tool](https://github.com/recrof/nrf_dfu_py) ![GitHub Repo stars](https://img.shields.io/github/stars/recrof/nrf_dfu_py?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/recrof/nrf_dfu_py?label=last%20updated) | Cross-platform nRF51/nRF52 Bluetooth DFU tool with GUI and CLI. |
| [XIAO nRF52 Updater](https://github.com/recrof/xiao_nrf52_updater) ![GitHub Repo stars](https://img.shields.io/github/stars/recrof/xiao_nrf52_updater?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/recrof/xiao_nrf52_updater?label=last%20updated) | Updater firmware that flashes nearby nRF52 nodes over Bluetooth DFU. |
| [Heltec V4.2 Multi-Boot Selector](https://github.com/Finmacjones/HeltecV4.2MultiBoot) ![GitHub Repo stars](https://img.shields.io/github/stars/Finmacjones/HeltecV4.2MultiBoot?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Finmacjones/HeltecV4.2MultiBoot?label=last%20updated) | **Heltec WiFi LoRa 32 V4.2 (ESP32-S3).** 4 OTA slots (3 MB each) in 16 MB flash; switches between Meshtastic, MeshCore, RNode and a spare slot via OLED menu and USER button, with per-firmware NVS/filesystem isolation. |
| [Drone MeshCore Updater](https://github.com/recrof/drone_meshcore_updater) ![GitHub Repo stars](https://img.shields.io/github/stars/recrof/drone_meshcore_updater?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/recrof/drone_meshcore_updater?label=last%20updated) | Zephyr firmware for Seeed XIAO boards that carries firmware bundles to unreachable repeaters by drone or on foot and flashes over BLE DFU, with a PWA web client. |
| [MeshForge](https://github.com/MeshEnvy/mesh-forge) ![GitHub Repo stars](https://img.shields.io/github/stars/MeshEnvy/mesh-forge?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/MeshEnvy/mesh-forge?label=last%20updated) | Cloud firmware builder and web flasher for LoRa mesh devices. |
| [MeshCore Custom Firmware Builder](https://github.com/christian45410/meshcore-cfw-builder) ![GitHub Repo stars](https://img.shields.io/github/stars/christian45410/meshcore-cfw-builder?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/christian45410/meshcore-cfw-builder?label=last%20updated) | **All MeshCore-supported ESP32 boards.** Web-based firmware builder: select board, firmware type and custom flags, get a compiled .bin back. |
| [MeshCore-OTA-Flasher](https://github.com/Dreikor17/MeshCore-OTA-Flasher) ![GitHub Repo stars](https://img.shields.io/github/stars/Dreikor17/MeshCore-OTA-Flasher?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Dreikor17/MeshCore-OTA-Flasher?label=last%20updated) | Windows tool for nRF52840 firmware updates over Bluetooth LE. |
| [Mesh America Device Configurator](https://meshamerica.com/device-configurator/) 🔒 | Browser flasher and configurator over Web Serial. |
| [weebl2000's Firmware Builder](https://mcimages.weebl.me/) 🔒 | **All MeshCore-supported boards.** Build and download firmware images for your device. |

## Libraries and SDKs

| Project Name | Description |
| :--- | :--- |
| [meshcore-cli](https://github.com/meshcore-dev/meshcore-cli) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-dev/meshcore-cli?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/meshcore-dev/meshcore-cli?label=last%20updated) | Official command line interface for nodes. |
| [meshcore_py](https://github.com/meshcore-dev/meshcore_py) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-dev/meshcore_py?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/meshcore-dev/meshcore_py?label=last%20updated) | Official Python bindings over serial, BLE and TCP. |
| [openHop Core](https://github.com/openhop-dev/openhop_core) ![GitHub Repo stars](https://img.shields.io/github/stars/openhop-dev/openhop_core?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/openhop-dev/openhop_core?label=last%20updated) | Python reimplementation of the protocol and routing stack, with direct SX1262 support. |
| [meshcore.js](https://github.com/meshcore-dev/meshcore.js) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-dev/meshcore.js?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/meshcore-dev/meshcore.js?label=last%20updated) | Official JavaScript companion radio library. |
| [meshcore-pi](https://github.com/brianwiddas/meshcore-pi) ![GitHub Repo stars](https://img.shields.io/github/stars/brianwiddas/meshcore-pi?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/brianwiddas/meshcore-pi?label=last%20updated) | Python protocol implementation for Raspberry Pi and other Linux hosts. |
| [meshcore-c (Nicolai-Electronics)](https://github.com/Nicolai-Electronics/meshcore-c) ![GitHub Repo stars](https://img.shields.io/github/stars/Nicolai-Electronics/meshcore-c?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Nicolai-Electronics/meshcore-c?label=last%20updated) | Dependency-free MeshCore protocol implementation in C for ESP-IDF projects. |
| [pyMC WM1303](https://github.com/HansvanMeer/pyMC_WM1303) ![GitHub Repo stars](https://img.shields.io/github/stars/HansvanMeer/pyMC_WM1303?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/HansvanMeer/pyMC_WM1303?label=last%20updated) | Multi-channel LoRa bridge turning an SX1302/SX1303 concentrator into a MeshCore gateway. |
| [meshcore-go](https://github.com/meshcore-go/meshcore-go) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-go/meshcore-go?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/meshcore-go/meshcore-go?label=last%20updated) | Pure Go protocol implementation. |
| [meshcore-rs](https://github.com/andrewdavidmackenzie/meshcore-rs) ![GitHub Repo stars](https://img.shields.io/github/stars/andrewdavidmackenzie/meshcore-rs?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/andrewdavidmackenzie/meshcore-rs?label=last%20updated) | Rust port of the Python library. |
| [meshcore_upy](https://github.com/fdlamotte/meshcore_upy) ![GitHub Repo stars](https://img.shields.io/github/stars/fdlamotte/meshcore_upy?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/fdlamotte/meshcore_upy?label=last%20updated) | MicroPython bindings. |
| [MeshCoreKmp](https://github.com/Wavesonics/MeshCoreKmp) ![GitHub Repo stars](https://img.shields.io/github/stars/Wavesonics/MeshCoreKmp?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Wavesonics/MeshCoreKmp?label=last%20updated) | Kotlin Multiplatform library for BLE companion nodes. |
| [meshcore-go (meshcore-cz)](https://github.com/meshcore-cz/meshcore-go) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-cz/meshcore-go?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/meshcore-cz/meshcore-go?label=last%20updated) | Transport-independent Go SDK over serial, BLE and TCP. |
| [meshcore_client](https://github.com/dz0ny/meshcore_client) ![GitHub Repo stars](https://img.shields.io/github/stars/dz0ny/meshcore_client?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/dz0ny/meshcore_client?label=last%20updated) | Flutter/Dart implementation of the BLE companion protocol. |
| [meshcore-packets-java](https://github.com/msmuenchen/meshcore-packets-java) ![GitHub Repo stars](https://img.shields.io/github/stars/msmuenchen/meshcore-packets-java?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/msmuenchen/meshcore-packets-java?label=last%20updated) | Java packet encoder and decoder. |
| [MeshCoreCompanion (meshcore_c)](https://github.com/SH3D/meshcore_c) ![GitHub Repo stars](https://img.shields.io/github/stars/SH3D/meshcore_c?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/SH3D/meshcore_c?label=last%20updated) | Portable C99 companion protocol library with an Arduino C++ wrapper (ESP32, nRF52, STM32, desktop). |
| [meshcore-ts](https://github.com/dpup/meshcore-ts) ![GitHub Repo stars](https://img.shields.io/github/stars/dpup/meshcore-ts?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/dpup/meshcore-ts?label=last%20updated) | Typed TypeScript client over TCP/WiFi and USB serial. |
| [meshpkt](https://github.com/meshcore-cz/meshpkt) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-cz/meshpkt?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/meshcore-cz/meshpkt?label=last%20updated) | Pure Go packet codec with identity cryptography and TypeScript WebAssembly bindings. |

## Integrations and Bots

| Project Name | Connection | Description |
| :--- | :---: | :--- |
| [Meshpoint](https://github.com/KMX415/meshpoint) ![GitHub Repo stars](https://img.shields.io/github/stars/KMX415/meshpoint?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/KMX415/meshpoint?label=last%20updated) | — | Raspberry Pi base station using an SX1302/SX1303 LoRa concentrator. |
| [openHop Repeater](https://github.com/openhop-dev/openhop_repeater) ![GitHub Repo stars](https://img.shields.io/github/stars/openhop-dev/openhop_repeater?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/openhop-dev/openhop_repeater?label=last%20updated) | — | Python repeater daemon for Pi-class and embedded Linux hardware, built on openHop Core. |
| [meshcore-ha](https://github.com/meshcore-dev/meshcore-ha) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-dev/meshcore-ha?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/meshcore-dev/meshcore-ha?label=last%20updated) | — | Official Home Assistant integration, installable via HACS. |
| [meshcore-bot](https://github.com/agessaman/meshcore-bot) ![GitHub Repo stars](https://img.shields.io/github/stars/agessaman/meshcore-bot?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/agessaman/meshcore-bot?label=last%20updated) | Serial, BLE or TCP/IP | Python command bot with Discord and Telegram bridging plus a web viewer. |
| [meshcoretomqtt](https://github.com/Cisien/meshcoretomqtt) ![GitHub Repo stars](https://img.shields.io/github/stars/Cisien/meshcoretomqtt?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Cisien/meshcoretomqtt?label=last%20updated) | MQTT | Publishes debug and packet capture output to MQTT. |
| [Akita Meshtastic Meshcore Bridge](https://github.com/AkitaEngineering/Akita-Meshtastic-Meshcore-Bridge) ![GitHub Repo stars](https://img.shields.io/github/stars/AkitaEngineering/Akita-Meshtastic-Meshcore-Bridge?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/AkitaEngineering/Akita-Meshtastic-Meshcore-Bridge?label=last%20updated) | — | Bidirectional bridge between Meshtastic and MeshCore over serial or MQTT. |
| [MeshCore-BitChat](https://github.com/jooray/MeshCore-BitChat) ![GitHub Repo stars](https://img.shields.io/github/stars/jooray/MeshCore-BitChat?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/jooray/MeshCore-BitChat?label=last%20updated) | — | Experimental fork branch bridging Bitchat and MeshCore mesh messages. |
| [Meshcore-Repeater-MQTT-Gateway](https://github.com/jmead/Meshcore-Repeater-MQTT-Gateway) ![GitHub Repo stars](https://img.shields.io/github/stars/jmead/Meshcore-Repeater-MQTT-Gateway?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/jmead/Meshcore-Repeater-MQTT-Gateway?label=last%20updated) | MQTT | Gateway firmware bridging repeaters to MQTT. |
| [MeshCore ATAK Plugin](https://github.com/atakmaps/TAK-MESHCORE) ![GitHub Repo stars](https://img.shields.io/github/stars/atakmaps/TAK-MESHCORE?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/atakmaps/TAK-MESHCORE?label=last%20updated) | — | ATAK plugin for the MeshCore BLE companion transport. |
| [Mesh-Citadel BBS](https://github.com/taedryn/mesh-citadel) ![GitHub Repo stars](https://img.shields.io/github/stars/taedryn/mesh-citadel?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/taedryn/mesh-citadel?label=last%20updated) | — | Citadel-style BBS reachable over the mesh, inspired by 80s Citadel BBSes. |
| [meshcore-mqtt](https://github.com/ipnet-mesh/meshcore-mqtt) ![GitHub Repo stars](https://img.shields.io/github/stars/ipnet-mesh/meshcore-mqtt?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/ipnet-mesh/meshcore-mqtt?label=last%20updated) | Serial, BLE or TCP | MQTT bridge with TLS support. |
| [BinktermPHP](https://github.com/awehttam/binkterm-php) ![GitHub Repo stars](https://img.shields.io/github/stars/awehttam/binkterm-php?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/awehttam/binkterm-php?label=last%20updated) | — | Full-stack Bulletin Board System with a MeshCore gateway, web and telnet access, and FidoNet. |
| [map.meshcore.io uploader](https://github.com/recrof/map.meshcore.io-uploader) ![GitHub Repo stars](https://img.shields.io/github/stars/recrof/map.meshcore.io-uploader?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/recrof/map.meshcore.io-uploader?label=last%20updated) | Serial | Uploads every repeater and room server a companion hears to the public map. |
| [meshcore-mqtt-broker (michaelhart)](https://github.com/michaelhart/meshcore-mqtt-broker) ![GitHub Repo stars](https://img.shields.io/github/stars/michaelhart/meshcore-mqtt-broker?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/michaelhart/meshcore-mqtt-broker?label=last%20updated) | — | WebSocket MQTT broker authenticating clients with MeshCore public keys. |
| [Cyclenerd MeshCore Bot](https://github.com/Cyclenerd/meshcore-bot) ![GitHub Repo stars](https://img.shields.io/github/stars/Cyclenerd/meshcore-bot?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Cyclenerd/meshcore-bot?label=last%20updated) | Serial | Node.js command bot with scheduled repeater status collection. |
| [meshcore-card](https://github.com/jpettitt/meshcore-card) ![GitHub Repo stars](https://img.shields.io/github/stars/jpettitt/meshcore-card?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/jpettitt/meshcore-card?label=last%20updated) | — | Home Assistant Lovelace cards for hub, node, contact and channel statistics. |
| [Akita Zmodem MeshCore](https://github.com/AkitaEngineering/Akita-Zmodem-MeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/AkitaEngineering/Akita-Zmodem-MeshCore?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/AkitaEngineering/Akita-Zmodem-MeshCore?label=last%20updated) | — | Lightweight ZMODEM-style file transfer protocol over the MeshCore companion client. |
| [MeshCore Chat for Home Assistant](https://github.com/mwolter805/meshcore-ha-chat) ![GitHub Repo stars](https://img.shields.io/github/stars/mwolter805/meshcore-ha-chat?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/mwolter805/meshcore-ha-chat?label=last%20updated) | — | Sidebar chat panel and persistent message store built on meshcore-ha. |
| [openHop Modem](https://github.com/openhop-dev/openhop_modem) ![GitHub Repo stars](https://img.shields.io/github/stars/openhop-dev/openhop_modem?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/openhop-dev/openhop_modem?label=last%20updated) | — | Turns an ESP32 or nRF52 SX1262 board into a dedicated LoRa modem for openHop Core. |
| [ESPHome MeshCore](https://github.com/netmilk/esphome-meshcore) ![GitHub Repo stars](https://img.shields.io/github/stars/netmilk/esphome-meshcore?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/netmilk/esphome-meshcore?label=last%20updated) | — | ESPHome component turning XIAO nRF52840 boards into managed MeshCore sensor nodes; control switches, sensors, fans and lights over LoRa mesh from the Companion app. |
| [MeshCore ESP-NOW Filtered Bridge](https://github.com/Department-of-Mesh-Regional-Bridging/meshcore-esp-now-filtered-bridge) ![GitHub Repo stars](https://img.shields.io/github/stars/Department-of-Mesh-Regional-Bridging/meshcore-esp-now-filtered-bridge?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Department-of-Mesh-Regional-Bridging/meshcore-esp-now-filtered-bridge?label=last%20updated) | — | MeshCore to ESP-NOW bridge with configurable packet filtering. |
| [Raven](https://github.com/kn6plv/Raven) ![GitHub Repo stars](https://img.shields.io/github/stars/kn6plv/Raven?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/kn6plv/Raven?label=last%20updated) | — | Bridges AREDN mesh messages to MeshCore, Meshtastic and Winlink. |
| [MeshCore WeatherBot](https://github.com/recrof/MeshCore-WeatherBot) ![GitHub Repo stars](https://img.shields.io/github/stars/recrof/MeshCore-WeatherBot?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/recrof/MeshCore-WeatherBot?label=last%20updated) | — | Node.js weather forecast and lightning alert bot for mesh channels. |
| [MeshCore Discord Bridge](https://github.com/Hude06/MeshCoreDiscordBridge) ![GitHub Repo stars](https://img.shields.io/github/stars/Hude06/MeshCoreDiscordBridge?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Hude06/MeshCoreDiscordBridge?label=last%20updated) | Serial | Bidirectional Discord bridge with multi-channel routing and flood protection. |
| [MeshCore Home Assistant Panel v2](https://github.com/d3sbo/MeshCore-Home-Assistant-Panel-v2) ![GitHub Repo stars](https://img.shields.io/github/stars/d3sbo/MeshCore-Home-Assistant-Panel-v2?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/d3sbo/MeshCore-Home-Assistant-Panel-v2?label=last%20updated) | — | Dashboard with interactive maps, heatmaps and playback recording for the mesh. |
| [openHop HA Integration](https://github.com/openhop-dev/openHop-HA-Integration) ![GitHub Repo stars](https://img.shields.io/github/stars/openhop-dev/openHop-HA-Integration?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/openhop-dev/openHop-HA-Integration?label=last%20updated) | — | Home Assistant integration for openHop Repeater with telemetry and control entities. |
| [Reticulum Smart MeshCore Interface](https://github.com/afit21/Reticulum-Smart-MeshCore-Interface) ![GitHub Repo stars](https://img.shields.io/github/stars/afit21/Reticulum-Smart-MeshCore-Interface?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/afit21/Reticulum-Smart-MeshCore-Interface?label=last%20updated) | — | Runs Reticulum LXMF and NomadNet over MeshCore repeaters without flooding the mesh. |
| [RNS Gateway](https://github.com/genemichael/rns-gateway) ![GitHub Repo stars](https://img.shields.io/github/stars/genemichael/rns-gateway?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/genemichael/rns-gateway?label=last%20updated) | — | Runs a Reticulum transport and TCP server alongside MeshCore firmware on one Heltec V4. |
| [MeshCore SAME EAS Alerter](https://github.com/Mambo430/MeshCore-SAME-EAS-Alerter) ![GitHub Repo stars](https://img.shields.io/github/stars/Mambo430/MeshCore-SAME-EAS-Alerter?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Mambo430/MeshCore-SAME-EAS-Alerter?label=last%20updated) | — | Forwards SAME emergency alert broadcasts onto the mesh. |
| [PokeMesh](https://github.com/IdreesInc/PokeMesh) ![GitHub Repo stars](https://img.shields.io/github/stars/IdreesInc/PokeMesh?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/IdreesInc/PokeMesh?label=last%20updated) | Serial | Collaborative Pokémon FireRed played through channel commands, turning the game into a text adventure over MeshCore. |
| [MeshBBS](https://github.com/atomozero/MeshBBS) ![GitHub Repo stars](https://img.shields.io/github/stars/atomozero/MeshBBS?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/atomozero/MeshBBS?label=last%20updated) | — | Bulletin board system with public boards and private messages over MeshCore. |
| [meshcore-bot (Go)](https://github.com/meshcore-go/meshcore-bot) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-go/meshcore-bot?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/meshcore-go/meshcore-bot?label=last%20updated) | — | Lightweight command bot in Go. |
| [Meshy (Upstate Mesh)](https://github.com/Upstate-Mesh/meshy) ![GitHub Repo stars](https://img.shields.io/github/stars/Upstate-Mesh/meshy?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Upstate-Mesh/meshy?label=last%20updated) | — | Scheduled bot for beaconing, weather forecasts and Home Assistant sensor reports. |
| [MeshCore Email Gateway](https://github.com/MGJ520/MeshCore-Email-Gateway) ![GitHub Repo stars](https://img.shields.io/github/stars/MGJ520/MeshCore-Email-Gateway?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/MGJ520/MeshCore-Email-Gateway?label=last%20updated) | — | Bidirectional SMTP/IMAP gateway with a management API and web interface. |
| [HopLink](https://github.com/A13xB0/hoplink) ![GitHub Repo stars](https://img.shields.io/github/stars/A13xB0/hoplink?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/A13xB0/hoplink?label=last%20updated) | TCP/IP | Bridge between MeshCore, Meshtastic and Discord. |
| [MeshCore BBS](https://github.com/carsten-walther/MeshCore-BBS) ![GitHub Repo stars](https://img.shields.io/github/stars/carsten-walther/MeshCore-BBS?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/carsten-walther/MeshCore-BBS?label=last%20updated) | — | Store-and-forward bulletin board running on a companion radio. |
| [MeshCore UI for Home Assistant](https://github.com/Ratty7198/MeshCore-HA-UI) ![GitHub Repo stars](https://img.shields.io/github/stars/Ratty7198/MeshCore-HA-UI?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Ratty7198/MeshCore-HA-UI?label=last%20updated) | — | HACS sidebar dashboard on top of meshcore-ha with chat, contacts and maps. |
| [meshcore-discord-relay](https://github.com/yellowcooln/meshcore-discord-relay) ![GitHub Repo stars](https://img.shields.io/github/stars/yellowcooln/meshcore-discord-relay?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/yellowcooln/meshcore-discord-relay?label=last%20updated) | MQTT | Relays MQTT traffic into Discord channels. |
| [meshcore-mcp](https://github.com/dpup/meshcore-mcp) ![GitHub Repo stars](https://img.shields.io/github/stars/dpup/meshcore-mcp?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/dpup/meshcore-mcp?label=last%20updated) | — | Model Context Protocol server exposing a node to AI agents. |
| [Domoticz MeshCore Plugin](https://github.com/galadril/Domoticz-MeshCore-Plugin) ![GitHub Repo stars](https://img.shields.io/github/stars/galadril/Domoticz-MeshCore-Plugin?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/galadril/Domoticz-MeshCore-Plugin?label=last%20updated) | — | Exposes nodes, telemetry and messaging as native Domoticz devices. |
| [MeshRes](https://github.com/bryantkelley/MeshRes) ![GitHub Repo stars](https://img.shields.io/github/stars/bryantkelley/MeshRes?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/bryantkelley/MeshRes?label=last%20updated) | — | Streams mesh messages into the Resonite social VR platform. |
| [Spectra](https://forge.hackers.town/Wrewdison/Spectra) | — | Rust bridge from MeshCore or Meshtastic radios to the Veilid DHT. |
| [Supply Drop BBS](https://supplydrop.meshamerica.com/) 🔒 | — | Rust BBS for Raspberry Pi with MeshCore and Meshtastic bridges and a plugin system for other transports. |

## Self-Hosted Dashboards

| Project Name | Description |
| :--- | :--- |
| [MeshMonitor](https://meshmonitor.org/) ([GitHub repository](https://github.com/Yeraze/meshmonitor)) ![GitHub Repo stars](https://img.shields.io/github/stars/Yeraze/meshmonitor?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Yeraze/meshmonitor?label=last%20updated) | Self-hosted multi-protocol dashboard (MeshCore + Meshtastic) with maps, telemetry and automation. |
| [PotatoMesh](https://github.com/l5yth/potato-mesh) ![GitHub Repo stars](https://img.shields.io/github/stars/l5yth/potato-mesh?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/l5yth/potato-mesh?label=last%20updated) | Federated dashboard for local communities with remote ingestors and a public API. |
| [Remote Terminal for MeshCore (jkingsman)](https://github.com/jkingsman/Remote-Terminal-for-MeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/jkingsman/Remote-Terminal-for-MeshCore?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/jkingsman/Remote-Terminal-for-MeshCore?label=last%20updated) | Power-user terminal with server-side packet capture, bots and MQTT integrations. |
| [CoreScope (Kpa-clawbot)](https://github.com/Kpa-clawbot/CoreScope) ![GitHub Repo stars](https://img.shields.io/github/stars/Kpa-clawbot/CoreScope?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Kpa-clawbot/CoreScope?label=last%20updated) | Packet analyzer with MQTT ingest, maps, channel chat and per-node analytics. |
| [OverMesh](https://github.com/Slofi/overmesh) ![GitHub Repo stars](https://img.shields.io/github/stars/Slofi/overmesh?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Slofi/overmesh?label=last%20updated) | Self-hosted dashboard for MeshCore and Meshtastic. |
| [MeshCore MQTT Live Map](https://github.com/yellowcooln/meshcore-mqtt-live-map) ![GitHub Repo stars](https://img.shields.io/github/stars/yellowcooln/meshcore-mqtt-live-map?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/yellowcooln/meshcore-mqtt-live-map?label=last%20updated) | Real-time traffic map with coverage, heat and line-of-sight views. |
| [mc-webui](https://github.com/MarekWo/mc-webui) ![GitHub Repo stars](https://img.shields.io/github/stars/MarekWo/mc-webui?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/MarekWo/mc-webui?label=last%20updated) | Flask web client with SQLite storage and Docker deployment. |
| [meshcore-hub](https://github.com/ipnet-mesh/meshcore-hub) ![GitHub Repo stars](https://img.shields.io/github/stars/ipnet-mesh/meshcore-hub?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/ipnet-mesh/meshcore-hub?label=last%20updated) | Collector, REST API and dashboard backed by PostgreSQL. (AI code) |
| [pyMC Console](https://github.com/Treehouse-00/pymc_console-dist) ![GitHub Repo stars](https://img.shields.io/github/stars/Treehouse-00/pymc_console-dist?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Treehouse-00/pymc_console-dist?label=last%20updated) | Real-time web dashboard for openHop Repeater with RF statistics and terrain mapping. |
| [MeshExplorer](https://github.com/ajvpot/meshexplorer) ![GitHub Repo stars](https://img.shields.io/github/stars/ajvpot/meshexplorer?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/ajvpot/meshexplorer?label=last%20updated) | Real-time map, chat client and packet analysis. |
| [MeshLog](https://github.com/Anrijs/MeshLog) ![GitHub Repo stars](https://img.shields.io/github/stars/Anrijs/MeshLog?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Anrijs/MeshLog?label=last%20updated) | PHP/MySQL web dashboard for the companion MeshCore logger firmware. |
| [Mesh Health Check](https://github.com/yellowcooln/meshcore-health-check) ![GitHub Repo stars](https://img.shields.io/github/stars/yellowcooln/meshcore-health-check?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/yellowcooln/meshcore-health-check?label=last%20updated) | Scores real-world message reachability across MQTT-connected observers. |
| [MeshCore Beacon](https://github.com/MeshCore-Beacon/beacon-server) ![GitHub Repo stars](https://img.shields.io/github/stars/MeshCore-Beacon/beacon-server?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/MeshCore-Beacon/beacon-server?label=last%20updated) | Go collector with PostgreSQL storage, WebSocket streaming and a React frontend. |
| [MeshCore Wardrive Map (Docker)](https://github.com/mintylinux/meshwar-map-docker) ![GitHub Repo stars](https://img.shields.io/github/stars/mintylinux/meshwar-map-docker?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/mintylinux/meshwar-map-docker?label=last%20updated) | Self-hosted SQLite-backed wardriving coverage map with no cloud dependency. |
| [openHop Repeater UI](https://github.com/openhop-dev/openHop_RepeaterUI) ![GitHub Repo stars](https://img.shields.io/github/stars/openhop-dev/openHop_RepeaterUI?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/openhop-dev/openHop_RepeaterUI?label=last%20updated) | Vue 3 web dashboard for monitoring and managing an openHop Repeater. |
| [LiteScope](https://github.com/RikoDEV/litescope) ![GitHub Repo stars](https://img.shields.io/github/stars/RikoDEV/litescope?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/RikoDEV/litescope?label=last%20updated) | Lightweight MQTT dashboard for node and telemetry monitoring. |
| [UK Mesh](https://www.ukmesh.com/) ([GitHub repository](https://github.com/gadgethd/ukmesh)) ![GitHub Repo stars](https://img.shields.io/github/stars/gadgethd/ukmesh?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/gadgethd/ukmesh?label=last%20updated) | Real-time analytics platform with observer ingestion, coverage and packet views. |
| [NOCT - Networked Off-grid Communications Terminal](https://noct.systems/) 🔒 | An all in one dashboard, bringing APRS, ADS-B, MeshCore, JS8Call, packet radio, Winlink email and GOES weather satellite data into one system. |

## Packet Analysis

| Project Name | Description |
| :--- | :--- |
| [meshcore-packet-capture](https://github.com/agessaman/meshcore-packet-capture) ![GitHub Repo stars](https://img.shields.io/github/stars/agessaman/meshcore-packet-capture?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/agessaman/meshcore-packet-capture?label=last%20updated) | Captures packets from a companion radio and publishes to MQTT. |
| [Lora Wideband Decoder](https://github.com/persistentcache/Lora-Wideband-Decoder) ![GitHub Repo stars](https://img.shields.io/github/stars/persistentcache/Lora-Wideband-Decoder?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/persistentcache/Lora-Wideband-Decoder?label=last%20updated) | SoapySDR wideband intercept receiver for LoRa traffic. |
| [meshcore-decoder](https://github.com/michaelhart/meshcore-decoder) ![GitHub Repo stars](https://img.shields.io/github/stars/michaelhart/meshcore-decoder?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/michaelhart/meshcore-decoder?label=last%20updated) | TypeScript library for decoding MeshCore packets with full cryptographic support. |
| [YAMPA](https://github.com/guax/YAMPA) ![GitHub Repo stars](https://img.shields.io/github/stars/guax/YAMPA?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/guax/YAMPA?label=last%20updated) | Yet another MeshCore packet analyser. |
| [MeshCore Signal Tester](https://github.com/kybl/meshcore-signal-tester) ![GitHub Repo stars](https://img.shields.io/github/stars/kybl/meshcore-signal-tester?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/kybl/meshcore-signal-tester?label=last%20updated) | Real-time signal tester for companions and repeaters, with per-repeater SNR/RSSI charts and a 3D signal map. [Web](https://meshcore.kyblsoft.cz/signal-tester) + Android app. |
| [MCSim](https://github.com/Brent-A/mcsim) ![GitHub Repo stars](https://img.shields.io/github/stars/Brent-A/mcsim?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Brent-A/mcsim?label=last%20updated) | Deterministic simulation framework for firmware testing. |
| [MeshCore Wireshark Dissector](https://github.com/aaronb/wireshark-meshcore) ![GitHub Repo stars](https://img.shields.io/github/stars/aaronb/wireshark-meshcore?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/aaronb/wireshark-meshcore?label=last%20updated) | Wireshark protocol dissector and pcapng converter. |
| [meshcore_sim](https://github.com/matthewdgreen/meshcore_sim) ![GitHub Repo stars](https://img.shields.io/github/stars/matthewdgreen/meshcore_sim?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/matthewdgreen/meshcore_sim?label=last%20updated) | Discrete-event simulator running real firmware routing logic. |
| [meshcore-decoder-py](https://github.com/chrisdavis2110/meshcore-decoder-py) ![GitHub Repo stars](https://img.shields.io/github/stars/chrisdavis2110/meshcore-decoder-py?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/chrisdavis2110/meshcore-decoder-py?label=last%20updated) | Python packet decoder. |
| [CoreScope (OKI-Mesh)](https://github.com/OKI-Mesh/CoreScope) ![GitHub Repo stars](https://img.shields.io/github/stars/OKI-Mesh/CoreScope?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/OKI-Mesh/CoreScope?label=last%20updated) | Live packet visualisation with replay and channel decryption. |
| [meshcore-packet-knife](https://github.com/jkingsman/meshcore-packet-knife) ![GitHub Repo stars](https://img.shields.io/github/stars/jkingsman/meshcore-packet-knife?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/jkingsman/meshcore-packet-knife?label=last%20updated) | Packet inspection and WebGPU hashtag channel key bruteforcing. |
| [MeshCute](https://github.com/MadScientistCH/meshcute) ![GitHub Repo stars](https://img.shields.io/github/stars/MadScientistCH/meshcute?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/MadScientistCH/meshcute?label=last%20updated) | Portable BLE, Wi-Fi and receive-only LoRa scanner for the M5Stack Cardputer Adv; universal toolbox for MeshCore/Meshtastic meetings. |
| [MeshCore Packet Tool](https://github.com/meshcore-cz/meshcore-packet-tool) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-cz/meshcore-packet-tool?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/meshcore-cz/meshcore-packet-tool?label=last%20updated) | Browser workbench for inspecting, decoding and crafting packets. |
| [meshcore-sim](https://github.com/dpup/meshcore-sim) ![GitHub Repo stars](https://img.shields.io/github/stars/dpup/meshcore-sim?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/dpup/meshcore-sim?label=last%20updated) | Deterministic network simulator for testing without radios. |

## Utilities

| Project Name | Description |
| :--- | :--- |
| [Reticulum Network Planner](https://github.com/0xSeren/Reticulum-Network-Planner) ![GitHub Repo stars](https://img.shields.io/github/stars/0xSeren/Reticulum-Network-Planner?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/0xSeren/Reticulum-Network-Planner?label=last%20updated) | *(Applies to all LoRa.)* Given a number of LoRa nodes and a geographical area, calculates optimal node positions from geographical data. |
| [MeshCore Proxy](https://github.com/rgregg/meshcore-proxy) ![GitHub Repo stars](https://img.shields.io/github/stars/rgregg/meshcore-proxy?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/rgregg/meshcore-proxy?label=last%20updated) | TCP proxy exposing a locally connected companion radio to remote clients. |
| [Offline Map Tile Downloader (Cyclenerd)](https://github.com/Cyclenerd/offline-map-tile-downloader) ![GitHub Repo stars](https://img.shields.io/github/stars/Cyclenerd/offline-map-tile-downloader?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/Cyclenerd/offline-map-tile-downloader?label=last%20updated) | Downloads offline OSM tiles for MeshCore, MeshOS and Meshtastic T-Deck apps. |
| [MeshCore Web Key Generator](https://github.com/agessaman/meshcore-web-keygen) ![GitHub Repo stars](https://img.shields.io/github/stars/agessaman/meshcore-web-keygen?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/agessaman/meshcore-web-keygen?label=last%20updated) | Browser-only Ed25519 key generator with custom public-key prefixes. |
| [Map Tiles Downloader](https://github.com/tekk/map-tiles-downloader) ![GitHub Repo stars](https://img.shields.io/github/stars/tekk/map-tiles-downloader?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/tekk/map-tiles-downloader?label=last%20updated) | Terminal utility for downloading offline OpenStreetMap tiles for mesh apps. |
| [MeshCore Utils (MC-Keygen)](https://github.com/samschlegel/meshcore-utils) ![GitHub Repo stars](https://img.shields.io/github/stars/samschlegel/meshcore-utils?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/samschlegel/meshcore-utils?label=last%20updated) | Rust vanity Ed25519 key generator with CUDA or Metal acceleration. (AI code) |
| [mc-keygen](https://github.com/samschlegel/mc-keygen) ![GitHub Repo stars](https://img.shields.io/github/stars/samschlegel/mc-keygen?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/samschlegel/mc-keygen?label=last%20updated) | Rust vanity Ed25519 key generator with CUDA or Metal acceleration. |
| [coresplitter](https://github.com/ogarcia/coresplitter) ![GitHub Repo stars](https://img.shields.io/github/stars/ogarcia/coresplitter?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/ogarcia/coresplitter?label=last%20updated) | Client multiplexer with SQLite cache sharing one companion radio among multiple TCP clients. |
| [MeshCore Channels catalog](https://github.com/marcelverdult/meshcore-channels) ![GitHub Repo stars](https://img.shields.io/github/stars/marcelverdult/meshcore-channels?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/marcelverdult/meshcore-channels?label=last%20updated) | Community-editable JSON catalog of MeshCore channels grouped by country. |
| [meshcore-tcp-mux](https://github.com/compumike/meshcore-tcp-mux) ![GitHub Repo stars](https://img.shields.io/github/stars/compumike/meshcore-tcp-mux?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/compumike/meshcore-tcp-mux?label=last%20updated) | Share one upstream MeshCore TCP companion with multiple downstream clients. |
| [MeshCore Regions catalog](https://github.com/marcelverdult/meshcore-regions) ![GitHub Repo stars](https://img.shields.io/github/stars/marcelverdult/meshcore-regions?style=social)<br>![Last updated](https://img.shields.io/github/last-commit/marcelverdult/meshcore-regions?label=last%20updated) | Community-editable JSON catalog of region codes used worldwide, allowing listing of public channels. |
| [Mesh Utility](https://mesh-utility.org/) 🔒 | Progressive Web App for mapping MeshCore LoRa coverage with optional cloud ingestion. |
| [MeshCore Web Keygen](https://gessaman.com/mc-keygen/) 🔒 | Client-side vanity Ed25519 key generator with custom hex prefixes. |
| [MeshCore Geo Prune](https://static.pixelentry.de/meshcore/geo-prune/) 🔒 | Browser tool that cleans the contact list with a geofence. |

## Maps and Diagnostics

Tools to see what is happening on the mesh.

### Maps

| Project / URL | Description |
| :--- | :--- |
| [#BEmesh map](https://meshmap.radio-actief.be/) | Belgian map with network stats and a configurator. |
| [Czech coverage map](https://pokryti.meshcore.cz/) | Czech coverage with terrain-aware planning. |
| [Greece CoreScope map](https://meshcore-greece.up.railway.app/#/live) | Live CoreScope instance for the Greek network. |
| [HanseMesh map](https://hansemesh.de/netzwerk/karte/) | Northern Germany repeater status and coverage. |
| [HopRadar](https://hopradar.net/) | Browser live map and analyzer for your own node over BLE or USB, with hop traces and SNR. |
| [Iceland analyzer](https://mc.flatuslifir.is/) | Live CoreScope instance for the Icelandic network. |
| [KernWi-Fi map](https://meshcore.kernwifi.com.au/map) | South Australian repeater and observer network. |
| [KiekR map](https://map.kiekr.app/) | Region coverage derived from neighbour observations uploaded by KiekR users. |
| [LocalMesh Germany map](https://localmesh.de/karte/) | German coverage with repeater directory. |
| [LocalMesh Netherlands map](https://localmesh.nl/en/map/) | Dutch network coverage. |
| [LoraMesh France map](https://loramesh.fr/carte/) | French coverage by region. |
| [m3sh.uk Map](https://m3sh.uk/contacts/) | UK network as seen from Oxfordshire. |
| [~map.meshradio.uk~](https://map.meshradio.uk/) | **[Offline]** Network analysis and visualization tool for the UK MeshRadio community. |
| [mapme.sh](https://mapme.sh/) | Crowdsourced coverage mapping with companion wardriving apps. |
| [MeshCore Europe map](https://meshcoreeurope.org/en/map/) | European repeater and room server coverage. |
| [MeshCore Map](https://map.meshcore.io/) | Official global map displaying static user uploads for repeaters and room servers. |
| [MeshCore Polska map](https://mapa.meshcorepolska.org/) | Polish clients, repeaters, room servers and sensors. |
| [MeshCore-de.fyi region map](https://umap.openstreetmap.de/en/map/meshcore-defyi_130650) | Editable uMap of regions, mainly Germany. See also [region-editing context](https://meshcore-de.fyi/meshcore:allgemeines:regions:reale-regions-in-repeatern) and [how to edit](https://meshcore-de.fyi/region_karte). |
| [MeshMapper](https://meshmapper.net/) | Wardriving coverage platform with regional instances and an open API. |
| [UK Mesh Network](https://app.ukmesh.com) | UK network with paths and live visualisation |

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
| [DEALORA](https://github.com/MarkSlusar/DEALORA) | Genetic-algorithm antenna design tool for LoRa devices including MeshCore and Meshtastic. |



## Guides and Learning

| Resource | Description |
| :--- | :--- |
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
| [DevTrends MeshCore overview](https://devtrends.ru/c/meshcore-dev-meshcore) | Russian-language technical overview covering node roles, memory model and getting started. |
| [Habr MeshCore series (NanoVHF)](https://habr.com/ru/articles/1056050/) | Russian-language multi-part explainer comparing MeshCore's routing to Meshtastic's flood network. |
| [LilyGo MeshCore guide (Chinese)](https://wiki.lilygo.cc/zh/open-source/meshcore/) | Chinese-language official guide covering supported devices, roles and firmware flashing. |
| [MeshCore QuickStart (The Comms Channel)](https://www.youtube.com/playlist?list=PLshzThxhw4O4WU_iZo3NmNZOv6KMrUuF9) | Nine-part video series walking through initial MeshCore setup. |
| [Seeed Studio ESP32 MeshCore guide (Chinese)](https://wiki.seeedstudio.com/cn/get_started_with_esp32s3_meshcore/) | Chinese-language guide for flashing and configuring the XIAO ESP32S3 repeater. |


## Communities

### Africa

#### South Africa

- [LoRa Mesh Comms ZA Discord](https://discord.gg/tKGFwFYvsT) - South African community coordinating Meshtastic and MeshCore repeaters, mainly around Cape Town.

### Asia

#### India

- [r/MeshCoreIndia](https://www.reddit.com/r/MeshCoreIndia/) - Early-stage Indian community sharing regional radio settings.

#### Israel

- [MeshCore Israel](https://meshcore.org.il) - The Israel Meshcore Network.

#### Kazakhstan

- [MeshCore Kazakhstan](https://meshcore.kz/) - National community site.

### Europe

#### Pan-European

- [MeshCore Europe](https://meshcoreeurope.org/) - Multilingual umbrella site with community directory, guides and maps.

#### Austria

- [CarinthiaMesh wiki](https://wiki.carinthiamesh.com/) - Carinthian regional wiki.
- [MeshCore AT Telegram group](https://t.me/meshcoreat) - Austrian community chat.
- [MeshCore Austria](https://meshcore.at/) - German-language documentation and setup guides.
- [MeshCore-Austria.at](https://www.meshcore-austria.at/doku.php?id=start) - German-language community wiki.

#### Belarus

- [MeshNetBY](https://mesh-net.by/) - Belarusian community with MeshCore setup guides and city Telegram groups; also covers Meshtastic.

#### Belgium

- [LoraMesh België](https://www.loramesh.be/) - Emergency communication network.
- [MeshCore België](https://meshcore.radio-actief.be/) - Community wiki and setup guides.
- [Meshpot](https://meshpot.be) - French-language, privacy-focused guide for Brussels residents.

#### Bulgaria

- [MeshCore Bulgaria](https://www.meshcore.bg/) - Bulgarian community with map, presets and Telegram group.

#### Czech Republic

- [MeshCore ČR](https://meshcore.cz/) - Czech-language community and documentation.

#### Denmark

- [MeshCore.dk](https://meshcore.dk/) - Danish community hub with setup docs, node map and a Facebook group.

#### Estonia

- [ESTMesh](https://wiki.estmesh.ee/en/home) - Estonian Meshtastic and MeshCore wiki with configuration docs, dashboards and a Discord server.

#### Finland

- [Mesh Pirkanmaa](https://meshpirkanmaa.org/) - Tampere and Pirkanmaa region community.

#### France

- [Île-de-France Mesh](https://wiki.mesh-idf.fr) - Paris region wiki; also covers Meshtastic.
- [LoraMesh France](https://loramesh.fr/) - French community with regional coverage.
- [MeshCore France](https://www.meshcore.fr/) - French network coordination.
- [MeshCore Paris](https://meshcore.paris/) - Paris and Greater Paris region network.

#### Germany

- [BSmesh](https://bsmesh.de/) - Greater Braunschweig network.
- [HanseMesh](https://hansemesh.de/) - Network around [Hamburg greater area](https://umap.openstreetmap.de/de/map/meshcore-defyi-region-map_130650?feature=Hansemesh#7/52.382306/10.563354), and tutorials.
- [BreMesh](https://hbme.sh/) - Network around [Bremen and Bremerhaven greater area](https://umap.openstreetmap.de/de/map/meshcore-defyi-region-map_130650?feature=bremesh#7/52.382306/10.563354), and tutorials.
- [PEmesh](https://www.pemesh.de/) - Network around Peine.
- [IsarMesh](https://isarmesh.de/) - Bavarian community forum.
- [LocalMesh Deutschland](https://www.localmesh.de/) - German emergency radio network with guides.
- [Münsterland Mesh](https://mcml.info/) - Münsterland region of North Rhine-Westphalia.
- [Mesh Dresden](https://meshdresden.eu/) - Dresden and wider Saxony community.
- [Mesh Rheinland](https://www.meshrheinland.de/) - Rheinland and western Germany community.
- [MeshCore DE Matrix room](https://matrix.to/#/#meshcore-netzwerk-de:matrix.org) - German community chat.
- [MeshCore DE Telegram group](https://t.me/meshcorede) - German community chat.
- [MeshCore Deutschland wiki](https://meshcore-de.fyi/) - German-language wiki hub with setup guides and regional group directory.
- [MeshCore Dresden](https://loramesh-dresden.de/) - Dresden network.
- [MeshCore Essen-Kettwig](https://jonathansalim.de/) - Public network around Essen-Kettwig in the Ruhr area.
- [MeshMitte](https://msh3.de/) - Central Germany community.
- [SaarMesh](https://saarmesh.de/) - Saarland regional network.

#### Greece

- [MeshCore Greece Discord](https://discord.gg/6KSQBqaTmw) - Greek community server for planning and running MeshCore networks.

#### Hungary

- [MeshCore Hungary](https://meshcore.hu/) - Hungarian community on 868 MHz with map and Telegram group.

#### Ireland

- [LoRa Project Ireland](https://loraproject.ie/) - Island of Ireland off-grid messaging community.
- [Mayo Mesh](https://mayomesh.net/#/) - County Mayo mesh radio user group.

#### Italy

- [LoRa Brescia](https://www.lorabrescia.it/) - Brescia group with Italian guides for flashing and configuring MeshCore repeaters; also covers Meshtastic and LoRa APRS.
- [MeshCore ITA](https://meshcore-ita.github.io/) - Italian-language documentation: setup guide, the shared Italian radio preset, hardware, CLI reference, troubleshooting, FAQ and glossary.
- [MeshCore ITA Telegram group](https://t.me/meshcore_ita) - Public group, per-region topics.
- [MeshCore Italia](https://www.meshcoreitalia.it) - Nationwide Italian mesh on the EU/UK narrow preset, with map and Telegram group.
- [MeshCore Repeater Guide Italia](https://codeberg.org/3yte/meshcore-italia) - Italian CLI guide for repeaters on the national mesh, with the regional scope tree and a [command wizard](https://3yte.codeberg.page/meshcore-italia/).

#### Latvia

- [Apraide.lv](https://apraide.lv/) - Latvian LoRa mesh community; also covers Meshtastic.

#### Lithuania

- [Atviras Tinklas](https://atvirastinklas.lt) - Lithuanian community with a CoreScope instance and Telegram group.

#### Luxembourg

- [MeshCore Luxembourg](https://www.meshcore.lu/) - Luxembourgish community page listing the associations running MeshCore infrastructure nationwide.

#### Netherlands

- [Dutch MeshCore](https://dutchmeshcore.nl/) - Dutch node directory and radio preset reference.
- [LocalMesh Nederland](https://www.localmesh.nl/) - Dutch emergency network with setup guides.
- [MeshCore Forum NL](https://forum.meshcore-net.nl/) - Dutch-language forum.
- [MeshCore Nederland](https://www.meshcore.nl/) - Dutch national site.
- [MeshWiki NL](https://meshwiki.nl/) - Collaborative Dutch documentation wiki.

#### Norway

- [MeshWiki.no](https://meshwiki.no/) - Norwegian documentation hub and preset reference.

#### Poland

- [LoRa MeshCore Polska](https://lorameshcore.pl/) - Nationwide Polish off-grid network on the EU/UK narrow preset.
- [MeshCore Podlasie](https://meshcore.podlasie.pl/) - Hobbyist network in the Podlasie region, with news, settings and a forum.
- [MeshCore Polska](https://meshcorepolska.org/) - Polish network coordination hub.
- [MeshGo](https://meshgo.pl/) - Polish community hub.

#### Portugal

- [MeshCore Portugal](https://meshcore.pt/) - Portuguese community site.

#### Romania

- [Brașov Mesh](https://brasovmesh.com/) - Brașov network on the EU/UK narrow preset.
- [MeshCore Iași](https://meshcore-iasi.ro/) - Iași network with a live dashboard.

#### Russia

- [MeshCore Krasnodar Telegram group](https://t.me/MeshCore_KRD) - Russian-language Krasnodar Krai community chat for MeshCore users.
- [MeshCore Moscow](https://meshcoretel.ru/) - Moscow network with a live telemetry map.
- [MeshCore Moscow Telegram group](https://t.me/meshcoremoscow) - Moscow community chat.
- [MeshCore North Caucasus Telegram group](https://t.me/meshtastic_stv) - Russian-language regional community coordinated through the skmesh.ru dashboard.
- [MeshCore Offline Network Telegram channel](https://t.me/MeshCore_offline_network) - Russian-language channel with news, guides, devices and firmware.
- [MeshCore Rostov-on-Don Telegram group](https://t.me/Meshcore_Rostov_na_Donu) - Russian-language group for repeater setup, firmware and coverage maps.
- [MeshCore Russian-language Telegram group](https://t.me/meshcore_rulang) - General Russian-language public for MeshCore, Meshtastic and Reticulum discussion.
- [MeshCore Saint Petersburg](https://meshcore.spb.ru/wiki/) - City wiki with hardware, flashing and repeater guides, plus a Telegram group.

#### Serbia

- [meshcore.rs](https://meshcore.rs/) - Serbian-language node registry and live map for the regional MeshCore network.

#### Slovakia

- [MeshCore Slovensko](https://mesh.om3kff.sk/) - Slovak national mesh with map and Discord.

#### Slovenia

- [MeshCore Slovenija](https://meshcore.si/) - Slovenian community with the regional preset and firmware links.

#### Spain

- [MeshCore Catalunya](https://docs.livemap-meshcorecat.com/) - Catalonia community with live map and documentation.
- [NomadMesh](https://nomadmesh.org/) - Alpujarra region community network.
- [Red Sierra Sur](https://sierrasur.github.io/) - Jaén province network.
- [RegionMesh España](https://www.regionmesh.com/es/) - Spanish-language community hub and guides.

#### Sweden

- [Meshat.se](https://meshcore.meshat.se/) - Swedish network map and resources.

#### Switzerland

- [MeshCore Switzerland](https://www.meshcore.ch/) - Swiss community site.

#### Ukraine

- [MeshCore Ukraine](https://meshcore-ua.net/) - Volunteer-run public mesh for resilient communication across Ukraine.

#### United Kingdom

- [IPNet](https://ipnt.uk/) - Ipswich hub with CoreScope dashboards and MQTT services.
- [LocalMesh UK](https://localmesh.co.uk/) - UK emergency network with city communities.
- [MeshCore Wales](https://meshcore.wales/) - Welsh regional settings and coordination.
- [MeshHub UK](https://meshhub.uk/) - National coordination platform.
- [NorthMesh](https://northmesh.co.uk/) - Northern England community network.
- [ScotMesh](https://scotmesh.net/) - Scottish community tools.

### North America

#### Canada

- [CascadiaMesh](https://cascadiamesh.org/) - Pacific Northwest network from Vancouver, BC through Washington and Oregon to Northern California, with a [Discord server](https://discord.gg/CnnDfER3Yt).
- [Greater Ottawa Mesh](https://ottawamesh.ca/) - Ottawa community; also covers Meshtastic.
- [MeshCore Canada](https://meshcore.ca/) - National site with provincial communities.
- [Montreal Mesh](https://www.montrealmesh.ca/en/) - Montreal area MeshCore and Meshtastic community.
- [Ridgeline Mesh](https://ridgeline.ve7kod.ca/) - Southwest British Columbia network on an alternate frequency to Salish Mesh.
- [Salish Mesh](https://salishmesh.net/) - Salish Sea region of southwest British Columbia.

#### United States

- [Austin Mesh](https://www.austinmesh.org/) - Austin, Texas community.
- [Bay Area MeshCore](https://bayareameshcore.org/) - San Francisco Bay Area network.
- [Central Washington Hackers Discord](https://discord.gg/XFSA9f5kqM) - Central Washington State hacker community with MeshCore activity.
- [Chicagoland Mesh](https://chicagolandmesh.org/) - Chicago-area MeshCore, Meshtastic and Reticulum community.
- [Colorado MeshCore](https://meshcore.coloradomesh.org/) - Colorado community and guides.
- [CT Mesh](https://ctmesh.org/) - Connecticut mesh technologies user group.
- [Eastern US MeshCore](https://eastme.sh/) - Eastern states network.
- [Emerald Coast Mesh](https://ecmesh.us/) - Mesh community along the Emerald Coast in the Florida panhandle.
- [Florida Mesh](https://areyoumeshingwith.us/) - Florida-wide network run by amateur radio operators.
- [Florida MeshCore](https://mc.flmesh.us/) - Statewide community network for Florida.
- [Greater Boston Mesh](https://bostonme.sh/) - Boston-area community behind the Boston MeshCore MQTT dashboard.
- [Gulf Coast Mesh](https://gulfcoastmesh.org) - Louisiana and US Gulf Coast network.
- [Idaho Mesh](https://idahomesh.org) - Idaho network centred on the Treasure Valley.
- [Inland NW Mesh](https://inlandnwmesh.org/) - Spokane, Coeur d'Alene, the Palouse and Lewiston/Clarkston.
- [Kentucky Mesh](https://mesh-ky.org/) - Kentucky network; also covers Meshtastic.
- [Lehigh Valley Mesh](https://lvmesh.com/) - Lehigh Valley and eastern Pennsylvania.
- [Long Island Mesh](https://limesh.org/) - Long Island, New York network for MeshCore and Meshtastic.
- [Madison Mesh](https://madmesh.net/) - Community-owned network in Madison, Wisconsin.
- [Mesh America](https://meshamerica.com/) - Guides, wiki and network design articles.
- [MeshCore Lexington](https://meshcorelexington.com/) - Lexington, Kentucky network.
- [MeshCore TX](https://meshcoretx.net/) - Texas radio preset and repeater naming standard.
- [MeshNY](https://nyme.sh/) - New York City community.
- [MeshTexas](https://meshtexas.org/) - Statewide Texas network with a shared MQTT broker.
- [Missouri Mesh](https://missourimesh.org/) - Missouri community; also covers Meshtastic.
- [Mountain West Mesh](https://mwmesh.com/) - Utah, Idaho and Wyoming network.
- [MSP Mesh](https://mspmesh.org/) - Minneapolis-Saint Paul and Greater Minnesota group.
- [Nebraska Mesh](https://www.nebraskamesh.net/) - Statewide Nebraska network.
- [Nevada Mesh](https://nvme.sh/) - Carson City, Reno and northern Nevada network.
- [New England Mesh](https://nhmesh.com/) - New England-wide community across CT, MA, NH and ME.
- [NodakMesh](https://nodakmesh.org/) - North Dakota community with wiki and guides.
- [NTX Mesh](https://ntxmesh.com/) - Dallas-Fort Worth and greater North Texas.
- [PhillyMesh](https://phillymesh.net/) - Philadelphia-area network and community.
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

### Oceania

#### Australia

- [EastMesh Australia](https://eastmesh.au/) - Eastern Australia community.
- [Mesh Brisbane User Group wiki](https://wiki.mbug.com.au/en/Meshcore/Settings) - Brisbane and South East Queensland settings.
- [MeshCore AUS wiki](https://wiki.meshcoreaus.org/) - Australian community documentation.
- [MeshSydney](https://meshsydney.com/) - Sydney configuration and coordination.
- [NSW Mesh](https://nswmesh.au/) - Sydney and New South Wales network with a community knowledge base.
- [Perth MeshCore](https://perth.meshcore.au/) - Western Australia network.

#### New Zealand

- [Meshed](https://meshed.kiwi/) - New Zealand community network.

### South America

#### Argentina

- [Mesh Argentina](https://mesharg.com.ar/) - Argentine community covering Meshtastic, MeshCore and Reticulum mesh networks.

#### Brazil

- [Mesh Sorocaba](https://www.meshsorocaba.org/) - Portuguese-language guides and community.
- [MeshCore Brasil Telegram group](https://t.me/meshcorebrasil) - Brazilian community chat.

#### Chile

- [MeshChile](https://meshchile.cl/) - Chilean community with MeshCore guides, Discord and a [GitHub org](https://github.com/Mesh-Chile).

<a id="home-button" href="#contents">Home</a>

<script>
document.querySelectorAll('a[href]').forEach(function (a) {
  if (a.getAttribute('href').charAt(0) === '#') return;
  a.target = '_blank';
  a.rel = 'noopener noreferrer';
});
</script>
