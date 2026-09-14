# Awesome MeshCore [![Awesome list badge](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome MeshCore resources. Pull requests welcome!

MeshCore is a multi-platform system for enabling secure text based
communications utilising LoRa radio hardware. It can be used for off-grid
communication, emergency response & disaster recovery, outdoor activities,
tactical security including law enforcement, private security and also IoT
sensor networks.

## Table of contents

- [Official Resources](#official-resources)
  - [Social Media](#social-media)
- [Client](#client)
  - [Open Source](#open-source)
  - [Closed Source](#closed-source)
- [Libraries and SDKs](#libraries-and-sdks)
- [Integrations and Bots](#integrations-and-bots)
- [Self-Hosted Dashboards](#self-hosted-dashboards)
- [Packet Analysis](#packet-analysis)
- [Firmware and Flashing](#firmware-and-flashing)
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
  - [Canada](#canada)
  - [Czech Republic](#czech-republic)
  - [Europe](#europe)
  - [France](#france)
  - [Germany](#germany)
  - [Ireland](#ireland)
  - [Italy](#italy)
  - [Netherlands](#netherlands)
  - [New Zealand](#new-zealand)
  - [Poland](#poland)
  - [Portugal](#portugal)
  - [Spain](#spain)
  - [Sweden](#sweden)
  - [Switzerland](#switzerland)
  - [United Kingdom](#united-kingdom)
  - [United States](#united-states)

--------------------

## Official Resources

Everything from the official MeshCore project:

- [MeshCore.io](https://meshcore.io/) - the official homepage
- [Documentation](https://docs.meshcore.io/) - official docs
- [Blog](https://blog.meshcore.io/) - official announcements and releases
- [MeshCore Web Flasher](https://flasher.meshcore.io/)
- [MeshCore Map](https://map.meshcore.io/) - official network map
- [The FAQ](https://github.com/meshcore-dev/MeshCore/blob/main/docs/faq.md)
- [Firmware repository](https://github.com/meshcore-dev/MeshCore) - MIT licensed firmware

### Social Media

- [Discord](https://meshcore.gg) - official server
- [Reddit](https://reddit.com/r/meshcore)
- [Facebook group](https://www.facebook.com/groups/meshcore)
- [Mastodon](https://mastodon.social/@meshcore)
- [X](https://x.com/mesh_core)
- [YouTube](https://www.youtube.com/@meshcore-official)

## Client

### Open Source

- [MeshCore Open](https://github.com/zjs81/meshcore-open)
- [MeshCore gui](https://github.com/pe1hvh/meshcore-gui)
- [meshcore-mobile-app](https://github.com/thatSFguy/meshcore-mobile-app) - hardened Android client, no Google Play Services required
- [meshtrax](https://github.com/venamartin/meshtrax) - Flutter Android client with mapping and messaging
- [MeshCoreOne](https://github.com/Avi0n/MeshCoreOne) - native Swift client for iOS, macOS and watchOS
- [PommeCore](https://github.com/mbedworth/PommeCore) - SwiftUI companion app for Apple platforms
- [Offband MeshCore](https://github.com/OffbandMesh/meshcore-client) - cross-platform client with direct and channel chat
- [MeshApp](https://github.com/smikme/meshapp) - desktop client for MeshCore and Meshtastic with telemetry views
- [mesh-client](https://github.com/Colorado-Mesh/mesh-client) - Electron desktop client for MeshCore, Meshtastic and Reticulum
- [QMeshcoreApp](https://github.com/FelixvdDonk/QMeshcoreApp) - Qt6/QML desktop companion with BLE/serial, map and RX log
- [PyMeshCoreGUI](https://github.com/bliksemlabs/PyMeshCoreGUI) - Qt6 and Python desktop client
- [MeshCoreQt](https://github.com/zhrkvl/MeshCoreQt) - Qt desktop client
- [meshy](https://codeberg.org/sesivany/meshy) - GTK4/libadwaita client for Linux and macOS
- [meshcore-web (aXistem)](https://github.com/aXistem-dev/meshcore-web) - Docker-ready browser build of the companion app over BLE or USB
- [meshcore-webui](https://github.com/adradr/meshcore-webui) - web UI for managing devices and chatting on the mesh
- [meshtui](https://github.com/ekollof/meshtui) - Textual terminal client with delivery tracking and device management
- [tui-meshcore](https://github.com/guax/tui-meshcore) - terminal chat client with persistent history and regional presets
- [QTC](https://github.com/initsixdev/QTC) - old-school terminal client for Linux and macOS
- [Remote Terminal for MeshCore](https://github.com/MichTronics/Remote-Terminal-for-MeshCore) - remote terminal for repeaters with packet capture and MQTT
- [Meshcore-Wardrive-Android](https://github.com/mintylinux/Meshcore-Wardrive-Android) - Flutter wardriving app for mapping coverage
- [meshcore-web (Vue)](https://github.com/liamcottle/meshcore-web) - early Vue web client, superseded by the official app

### Closed Source

- [Official app](https://files.liamcottle.net/MeshCore/) also on google play, app store, etc
- [MeshOS](https://www.meshcore.co.uk/meshos) - licensed companion app and standalone firmware from MeshCore.co.uk
- [KIEKR](https://kiekr.app/)
- [MeshCore-TEAM](https://play.google.com/store/apps/details?id=com.meshcore.team) - Android client focused on group operations
- [meshGO!](https://play.google.com/store/apps/details?id=com.meshcore.meshgo) - Android off-grid messaging client
- [MeshMapper](https://play.google.com/store/apps/details?id=net.meshmapper.app) - Android coverage mapping and wardriving app

## Libraries and SDKs

- [meshcore_py](https://github.com/meshcore-dev/meshcore_py) - official Python bindings over serial, BLE and TCP
- [meshcore.js](https://github.com/meshcore-dev/meshcore.js) - official JavaScript companion radio library
- [meshcore-cli](https://github.com/meshcore-dev/meshcore-cli) - official command line interface for nodes
- [meshcore-ts](https://github.com/dpup/meshcore-ts) - typed TypeScript client over TCP/WiFi and USB serial
- [meshcore-go](https://github.com/meshcore-go/meshcore-go) - pure Go protocol implementation
- [meshcore-rs](https://github.com/andrewdavidmackenzie/meshcore-rs) - Rust port of the Python library
- [meshcore_upy](https://github.com/fdlamotte/meshcore_upy) - MicroPython bindings
- [meshcore-packets-java](https://github.com/msmuenchen/meshcore-packets-java) - Java packet encoder and decoder

## Integrations and Bots

- [meshcore-ha](https://github.com/meshcore-dev/meshcore-ha) - official Home Assistant integration, installable via HACS
- [meshcore-mqtt](https://github.com/ipnet-mesh/meshcore-mqtt) - MQTT bridge over serial, BLE or TCP with TLS support
- [Meshcore-Repeater-MQTT-Gateway](https://github.com/jmead/Meshcore-Repeater-MQTT-Gateway) - gateway firmware bridging repeaters to MQTT
- [meshcore-mcp](https://github.com/dpup/meshcore-mcp) - Model Context Protocol server exposing a node to AI agents
- [meshcore-bot](https://github.com/agessaman/meshcore-bot) - Python bot with Discord and Telegram bridging plus web viewer
- [meshcore-bot (Go)](https://github.com/meshcore-go/meshcore-bot) - lightweight bot in Go
- [meshcore-discord-relay](https://github.com/yellowcooln/meshcore-discord-relay) - relays MQTT traffic into Discord channels

## Self-Hosted Dashboards

- [mc-webui](https://github.com/MarekWo/mc-webui) - Flask web client with SQLite storage and Docker deployment
- [meshcore-hub](https://github.com/ipnet-mesh/meshcore-hub) - collector, REST API and dashboard backed by PostgreSQL
- [MeshMonitor](https://meshmonitor.org/) - self-hosted multi-protocol dashboard with maps, telemetry and automation

## Packet Analysis

- [meshcore-decoder](https://github.com/michaelhart/meshcore-decoder) - TypeScript packet decoder with full cryptographic support
- [meshcore-decoder-py](https://github.com/chrisdavis2110/meshcore-decoder-py) - Python packet decoder
- [wireshark-meshcore](https://github.com/aaronb/wireshark-meshcore) - Wireshark dissector and pcapng converter
- [YAMPA](https://github.com/guax/YAMPA) - yet another MeshCore packet analyser
- [CoreScope](https://github.com/OKI-Mesh/CoreScope) - live packet visualisation with replay and channel decryption
- [meshcore-packet-capture](https://github.com/agessaman/meshcore-packet-capture) - capture packets from a companion radio and publish to MQTT
- [meshcore-packet-knife](https://github.com/jkingsman/meshcore-packet-knife) - packet inspection and WebGPU hashtag channel key bruteforcing
- [meshcore-sim](https://github.com/dpup/meshcore-sim) - deterministic network simulator for testing without radios

## Firmware and Flashing

- [MeshCore-Solo](https://github.com/MarekZegare4/MeshCore-Solo) - companion firmware fork adding offline GPS navigation and GPX export
- [MeshCore-OTA-Flasher](https://github.com/Dreikor17/MeshCore-OTA-Flasher) - Windows tool for nRF52840 firmware updates over Bluetooth LE

## Maps and Diagnostics

Tools for the every-user to see whats going on in general.

### Maps

- [MeshCore Map](https://map.meshcore.dev/) - static user uploads
- [m3sh.uk Map](https://m3sh.uk/contacts/) - UK network as seen from Oxfordshire
- [mapme.sh](https://mapme.sh/) - crowdsourced coverage mapping with companion wardriving apps
- [MeshMapper](https://meshmapper.net/) - wardriving coverage platform with regional instances and an open API
- [MeshCore Europe map](https://meshcoreeurope.org/en/map/) - European repeater and room server coverage
- [LocalMesh Germany map](https://localmesh.de/karte/) - German coverage with repeater directory
- [LocalMesh Netherlands map](https://localmesh.nl/en/map/) - Dutch network coverage
- [HanseMesh map](https://hansemesh.de/netzwerk/karte/) - northern Germany repeater status and coverage
- [MeshCore Polska map](https://mapa.meshcorepolska.org/) - Polish clients, repeaters, room servers and sensors
- [LoraMesh France map](https://loramesh.fr/carte/) - French coverage by region
- [Czech coverage map](https://pokryti.meshcore.cz/) - Czech coverage with terrain-aware planning
- [KernWi-Fi map](https://meshcore.kernwifi.com.au/map) - South Australian repeater and observer network

### Diagnostics and Dashboards

- [EU Meshcore Analyzer](https://meshcore-analyzer.eu/) - live visual map of European MeshCore LoRa network traffic
- [MeshCore Analyzer (letsmesh)](https://analyzer.letsmesh.net/) - node connectivity, packet analysis and mesh health metrics
- [TennMesh Live](https://live.tennmesh.com/) - Tennessee telemetry with RF link analysis and routing loop detection
- [Boston MeshCore MQTT dashboard](https://mcmqttdashboard.bostonme.sh/) - live MQTT node presence and traffic metrics
- [KernWi-Fi live telemetry](https://meshcore.kernwifi.com.au/live) - South Australian live activity feed
- [MeshCore Tools](https://meshcore.envoyage.io/) - repeater configurator and region code lookup helpers

### RF Planning

- [MeshKit](https://meshkit.app/) - browser site planner with terrain LOS, Fresnel analysis and BLE radio tools
- [MeshOMatic](https://map.meshomatic.net/) - terrain-aware repeater placement planning and topology analysis

## Guides and Learning

- [Kev's Robots MeshCore course](https://www.kevsrobots.com/learn/meshcore/) - structured tutorial series from basics to flashing
- [Andy Kirby on YouTube](https://www.youtube.com/@andykirby) - hardware reviews, repeater builds and firmware walkthroughs
- [MeshCore.co.uk video collection](https://meshcore.co.uk/videos.html) - curated community videos
- [MeshCore Europe getting started](https://meshcoreeurope.org/en/get-started/) - multilingual introduction
- [MeshCore Europe repeater guide](https://meshcoreeurope.org/en/repeater-guide/) - repeater deployment walkthrough
- [NodakMesh wiki](https://nodakmesh.org/meshcore/wiki) - reference documentation and setup guides
- [Mesh America wiki](https://wiki.meshamerica.com/books/meshcore/page/start-here-meshcore-guide) - guides and protocol overview
- [J-Rat Techworks repeater guide](https://jrattechworks.com/meshcore-repeater-flashing-guide/) - flashing and repeater setup
- [Austin Mesh setup guide](https://www.austinmesh.org/join/meshcore-setup/) - beginner-friendly local setup
- [LocalMesh NL setup guide](https://www.localmesh.nl/en/meshcore-setup/) - Dutch-language beginner guide
- [Mesh Sorocaba configuração](https://www.meshsorocaba.org/configuracao/) - Portuguese-language setup documentation
- [WISSEN TECHNIK podcast](https://wissen-technik-meshcore-meshtastic.podigee.io/) - German-language podcast on MeshCore and Meshtastic

## Communities

### Virtual

- [r/MeshCore](https://reddit.com/r/meshcore) - official subreddit

### Australia

- [MeshCore AUS wiki](https://wiki.meshcoreaus.org/) - Australian community documentation
- [EastMesh Australia](https://eastmesh.au/) - eastern Australia community
- [MeshSydney](https://meshsydney.com/) - Sydney configuration and coordination
- [Perth MeshCore](https://perth.meshcore.au/) - Western Australia network

### Austria

- [MeshCore Austria](https://meshcore.at/) - German-language documentation and setup guides
- [CarinthiaMesh wiki](https://wiki.carinthiamesh.com/) - Carinthian regional wiki
- [MeshCore AT Telegram group](https://t.me/meshcoreat)

### Belgium

- [MeshCore België](https://meshcore.radio-actief.be/) - community wiki and setup guides
- [LoraMesh België](https://www.loramesh.be/) - emergency communication network

### Brazil

- [Mesh Sorocaba](https://www.meshsorocaba.org/) - Portuguese-language guides and community
- [MeshCore Brasil Telegram group](https://t.me/meshcorebrasil)

### Canada

- [MeshCore Canada](https://meshcore.ca/) - national site with provincial communities

### Czech Republic

- [MeshCore ČR](https://meshcore.cz/) - Czech-language community and documentation

### Europe

- [MeshCore Europe](https://meshcoreeurope.org/) - multilingual umbrella site with community directory, guides and maps

### France

- [MeshCore France](https://www.meshcore.fr/) - French network coordination
- [LoraMesh France](https://loramesh.fr/) - French community with regional coverage

### Germany

- [LocalMesh Deutschland](https://www.localmesh.de/) - German emergency radio network with guides
- [HanseMesh](https://hansemesh.de/) - northern Germany network and tutorials
- [IsarMesh](https://isarmesh.de/) - Bavarian community forum
- [MeshMitte](https://msh3.de/) - central Germany community
- [MeshCore DE Telegram group](https://t.me/meshcorede)

### Ireland

- [LoRa Project Ireland](https://loraproject.ie/) - island of Ireland off-grid messaging community

### Italy

- [MeshCore ITA](https://meshcore-ita.github.io/) - Italian-language documentation: setup guide, the shared Italian radio preset, hardware, CLI reference, troubleshooting, FAQ and glossary
- [MeshCore ITA Telegram group](https://t.me/meshcore_ita) - public group, per-region topics

### Netherlands

- [MeshCore Nederland](https://www.meshcore.nl/) - Dutch national site
- [LocalMesh Nederland](https://www.localmesh.nl/) - Dutch emergency network with setup guides
- [MeshCore Forum NL](https://forum.meshcore-net.nl/) - Dutch-language forum
- [MeshWiki NL](https://meshwiki.nl/) - collaborative Dutch documentation wiki

### New Zealand

- [Meshed](https://meshed.kiwi/) - New Zealand community network

### Poland

- [MeshCore Polska](https://mapa.meshcorepolska.org/) - Polish network map and coordination
- [MeshGo](https://meshgo.pl/) - Polish community hub

### Portugal

- [MeshCore Portugal](https://meshcore.pt/)

### Spain

- [RegionMesh España](https://www.regionmesh.com/es/) - Spanish-language community hub and guides
- [NomadMesh](https://nomadmesh.org/) - Alpujarra region community network

### Sweden

- [Meshat.se](https://meshcore.meshat.se/) - Swedish network map and resources

### Switzerland

- [MeshCore Switzerland](https://www.meshcore.ch/)

### United Kingdom

- [MeshCore.co.uk](https://meshcore.co.uk/) - UK community hub, MeshOS apps, device configurator and store (third-party, not the upstream project)
- [MeshHub UK](https://meshhub.uk/) - national coordination platform
- [LocalMesh UK](https://localmesh.co.uk/) - UK emergency network with city communities
- [MeshCore Wales](https://meshcore.wales/) - Welsh regional settings and coordination
- [NorthMesh](https://northmesh.co.uk/) - northern England community network
- [ScotMesh](https://scotmesh.mm7roq.compute.oarc.uk/) - Scottish community tools

### United States

- [RegionMesh](https://www.regionmesh.com/) - national hub with regional guides
- [Mesh America](https://meshamerica.com/) - guides, wiki and network design articles
- [Bay Area MeshCore](https://bayareameshcore.org/) - San Francisco Bay Area network
- [Eastern US MeshCore](https://eastme.sh/) - eastern states network
- [Denver MeshCore](https://denvermc.com/) - Denver metro community
- [Colorado MeshCore](https://meshcore.coloradomesh.org/) - Colorado community and guides
- [Mountain West Mesh](https://mwmesh.com/) - Utah, Idaho and Wyoming network
- [NodakMesh](https://nodakmesh.org/) - North Dakota community with wiki and guides
- [Austin Mesh](https://www.austinmesh.org/) - Austin, Texas community
- [Spokane Mesh](https://www.spokanemesh.net/) - Spokane regional network
- [TennMesh](https://live.tennmesh.com/) - Tennessee network and live monitor
