# Awesome Meshtastic List [![Awesome](./media/awesome-list-badge.svg)](https://awesome.re)

![Awesome Meshtastic List](media/awesome-meshtastic-list-logo.svg)

This is a curated list of useful resources, tools, tutorials, projects, and community contributions related to the Meshtastic open-source mesh communication project. Whether you're a beginner or advanced user, this list helps you explore and get the most out of your Meshtastic devices.

## Table of Contents

- [Official Source Code Repositories](#official-source-code-repositories)
  - [Core Repositories](#core-repositories)
  - [Mobile, Web and Desktop Clients](#mobile-web-and-desktop-clients)
  - [Device Interaction and Integrations](#device-interaction-and-integrations)
  - [Tools & Utilities](#tools--utilities)
  - [Hardware and Sensors](#hardware-and-sensors)
- [Projects](#projects)
  - [Fun Projects](#fun-projects)
- [Community](#community)
  - [Official](#official)
  - [Unofficial](#unofficial)
  - [Local Groups](#local-groups)
    - 🇦🇷 [Argentina](#argentina)
    - 🇦🇺 [Australia](#australia)
    - 🇧🇷 [Brazil](#brazil)
    - 🇧🇬 [Bulgaria](#bulgaria)
    - 🇨🇦 [Canada](#canada)
    - 🇨🇳 [China](#china)
    - 🇨🇴 [Colombia](#colombia)
    - 🇩🇰 [Denmark](#denmark)
    - 🇫🇮 [Finland](#finland)
    - 🇫🇷 [France](#france)
    - 🇩🇪 [Germany](#germany)
    - 🇮🇳 [India](#india)
    - 🇮🇱 [Israel](#israel)
    - 🇮🇹 [Italy](#italy)
    - 🇯🇵 [Japan](#japan)
    - 🇱🇻 [Latvia](#latvia)
    - 🇱🇹 [Lithuania](#lithuania)
    - 🇲🇽 [Mexico](#mexico)
    - 🇳🇱 [Netherlands, The](#netherlands-the)
    - 🇳🇿 [New Zealand](#new-zealand)
    - 🇵🇱 [Poland](#poland)
    - 🇸🇮 [Slovenia](#slovenia)
    - 🇿🇦 [South Africa](#south-africa)
    - 🇪🇸 [Spain](#spain)
    - 🇸🇪 [Sweden](#sweden)
    - 🇹🇼 [Taiwan](#taiwan)
    - 🇹🇷 [Türkiye](#türkiye)
    - 🇺🇦 [Ukraine](#ukraine)
    - 🇬🇧 [United Kingdom](#united-kingdom)
    - 🇺🇸 [United States](#united-states)
- [Contribute](#contribute)
- [Legal Notice](#legal-notice)
- [License](#license)

## Official Source Code Repositories

### Core Repositories

These repositories are at the heart of the Meshtastic project, containing firmware, APIs, and other essential code.

- [firmware](https://github.com/meshtastic/firmware) - Meshtastic device firmware
- [protobufs](https://github.com/meshtastic/protobufs) - Protobuf definitions for Meshtastic
- [web-flasher](https://github.com/meshtastic/web-flasher) - Online flasher for Meshtastic device firmware
- [meshtastic](https://github.com/meshtastic/meshtastic) - Meshtastic project website and documentation
- [api](https://github.com/meshtastic/api) - Meshtastic Website API

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### Mobile, Web and Desktop Clients

These repositories offer various client applications for different platforms.

- [web](https://github.com/meshtastic/web) - Meshtastic Web Client
- [Meshtastic-Apple](https://github.com/meshtastic/Meshtastic-Apple) - iOS, iPadOS & macOS Clients for Meshtastic
- [Meshtastic-Android](https://github.com/meshtastic/Meshtastic-Android) - Android app for Meshtastic
- [network-management-client](https://github.com/meshtastic/network-management-client) - Desktop client for offline deployment and mesh network management

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### Device Interaction and Integrations

Repositories related to firmware, device configuration, interactions and integrations

- [home-assistant](https://github.com/meshtastic/home-assistant) - Home Assistant integration for Meshtastic
- [python](https://github.com/meshtastic/python) - Python CLI and API for interacting with Meshtastic devices
- [node-red-contrib-meshtastic](https://github.com/meshtastic/node-red-contrib-meshtastic) - Node-RED integration for Meshtastic
- [Meshtastic-arduino](https://github.com/meshtastic/Meshtastic-arduino) - Arduino drivers for interfacing with Meshtastic nodes over WiFi and Serial
- [firmware-ota-wifi](https://github.com/meshtastic/firmware-ota-wifi) - WiFi-based OTA (Over The Air) firmware updates for Meshtastic devices
- [nrf52_factory_erase](https://github.com/meshtastic/nrf52_factory_erase) - Firmware for factory erasing the nRF52 chips used in Meshtastic devices
- [firmware-ota](https://github.com/meshtastic/firmware-ota) - BLE-OTA Mini firmware for Meshtastic devices
- [rust](https://github.com/meshtastic/rust) - A Rust library for interacting with Meshtastic radios
- [c-sharp](https://github.com/meshtastic/c-sharp) - C#/.NET command-line interface and library for Meshtastic

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### Tools & Utilities

For managing, simulating, and testing Meshtastic networks and devices.

- [meshtasticator](https://github.com/meshtastic/meshtasticator) - Simulator for Meshtastic, supporting discrete-event and interactive simulations
- [meshTestic](https://github.com/meshtastic/meshTestic) - End-to-end test suite for Meshtastic devices
- [meshtastic-site-planner](https://github.com/meshtastic/meshtastic-site-planner) - Site planning tool based on RF analysis using SPLAT! software
- [mqtt](https://github.com/meshtastic/mqtt) - MQTT broker boilerplate designed for Meshtastic’s native packet-aware MQTT support
- [RadioHead](https://github.com/meshtastic/RadioHead) - A fork of the RadioHead library, with custom fixes for Meshtastic devices

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### Hardware and Sensors

Repos related to the hardware components and sensor integration for Meshtastic.

- [antenna-reports](https://github.com/meshtastic/antenna-reports) - Community-contributed antenna testing reports and evaluations for Meshtastic devices
- [enclosures](https://github.com/meshtastic/enclosures) - 3D models for enclosures used in Meshtastic devices
- [i2c-sensor](https://github.com/meshtastic/i2c-sensor) - Arduino boilerplate for creating custom I2C sensors for Meshtastic
- [ETHClass2](https://github.com/meshtastic/ETHClass2) - Provides ETHClass2 integration for Meshtastic, originally from LilyGO T-ETH series

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

## Projects

### Fun Projects

- [MeshTIEstick: The Wearable LoRa Meshtastic Node](https://www.youtube.com/watch?v=2Wf6BcZS3AY) - Turning a necktie into a fully functional mesh node. 

## Community

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

## Official

- [Official Discord Server](https://discord.com/invite/ktMAKGBnBs)
- [Official Github Discussions](https://github.com/orgs/meshtastic/discussions)
- [Official Subreddit](https://www.reddit.com/r/meshtastic/)
- [Official Telegram](https://t.me/meshint)

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

## Unofficial

- [Meshtastic - English](https://t.me/meshtastic_eng) - <sub><sup>(Telegram)</sup></sub>
- [Official Discord Server](https://discord.com/invite/ktMAKGBnBs)
- [Official Subreddit](https://www.reddit.com/r/meshtastic/)

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

## Local Groups

A list of groups that have been actively setting up Meshtastic networks in their respective regions. For the official list of local groups, visit: [Meshtastic Local Groups](https://meshtastic.org/docs/community/local-groups/).

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇦🇷Argentina

- [Meshtastic Argentina Community](https://github.com/Meshtastic-Argentina/) - <sub><sup>(Github)</sup></sub>
- [Meshtastic Argentina Community](https://t.me/meshtastic_argentina) - <sub><sup>(Telegram)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇦🇺Australia

- [Meshtastic Australia](https://meshtastic.au) - <sub><sup>(Website)</sup></sub>
- Australian Capital Territory
  - [Canberra Meshtastic Community](https://www.meshcanberra.com/) - <sub><sup>(Website)</sup></sub>
  - [Canberra Meshtastic Community](https://discord.com/invite/4QgFsuaC3Z) - <sub><sup>(Discord)</sup></sub>
- New South Wales
  - [Meshtastic & Meshcore Sydney Community](https://www.facebook.com/groups/1041534027106861) - <sub><sup>(Facebook)</sup></sub>
  - [Sydney and Greater NSW Community](https://github.com/orgs/meshtastic/discussions/10) - <sub><sup>(Github Discussions)</sup></sub>
- Queensland
  - [Meshtastic Brisbane User Group](https://discord.com/invite/rN66wEedMY) - <sub><sup>(Discord)</sup></sub>
- Tasmania
  - [Meshtastic User Group Tasmania](https://www.facebook.com/groups/1556630645195649) - <sub><sup>(Facebook)</sup></sub>
- Victoria
  - [Melbourne Meshtastic Users, Australia](https://github.com/orgs/meshtastic/discussions/7) - <sub><sup>(Github Discussions)</sup></sub>
  - [Meshtastic Victoria](https://www.facebook.com/groups/meshtasticvictoria) - <sub><sup>(Facebook)</sup></sub>
  - [VicMesh - r/VicMesh](https://www.reddit.com/r/VicMesh/) - <sub><sup>(Reddit)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇧🇷Brazil

- [Meshtastic Community Brazil](https://t.me/meshtastic_br) - <sub><sup>(Telegram)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇧🇬Bulgaria

- [Meshtastic Community Bulgaria](https://facebook.com/groups/meshtasticbulgaria) - <sub><sup>(Facebook)</sup></sub>
- [Burgas Mesh](https://discord.gg/Kbs233rmq3) - <sub><sup>(Discord)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇨🇦Canada

- [Canadaverse Mesh Wiki](https://wiki.mt.gt/) - <sub><sup>(Website)</sup></sub>
- [Mesh Canada](https://t.me/meshtastic_canada) - <sub><sup>(Telegram)</sup></sub>
- [r/meshtasticCanada](https://www.reddit.com/r/meshtasticCanada/) - <sub><sup>(Reddit)</sup></sub>
- Alberta
  - [Mesht Alberta](https://t.me/meshtAlta) - <sub><sup>(Telegram)</sup></sub>
  - [Mesht Calgary](https://t.me/meshtcalgary) - <sub><sup>(Telegram)</sup></sub>
  - [Meshtastic Calgary](https://t.me/+LzO9qeIC7Ok2YTVh) - <sub><sup>(Telegram)</sup></sub>
  - [YYC Mesh](https://yycmesh.com/) - <sub><sup>(Website)</sup></sub>
- British Columbia
  - [Meshtastic BC users group](https://matrix.to/#/!kKfPDGFNasdKxwulZL:matrix.org?via=matrix.org) - <sub><sup>(Matrix)</sup></sub>
  - [Meshtastic BC users group](https://t.me/Mesh_BC) - <sub><sup>(Telegram)</sup></sub>
  - [Meshtastic Dawson Creek BC users group](https://t.me/Mesh_BC_Dawson_Creek) - <sub><sup>(Telegram)</sup></sub>
- Manitoba
  - [Mesht Manitoba](https://t.me/MeshtManitoba) - <sub><sup>(Telegram)</sup></sub>
- New Brunswick
  - [Mesht New Brunswick](https://t.me/MeshtNB) - <sub><sup>(Telegram)</sup></sub>
- Newfoundland and Labrador
  - [Mesht Newfoundland](https://t.me/MeshtNewfoundland) - <sub><sup>(Telegram)</sup></sub>
- Northwest Territories, Yukon and Nunavut
  - [Mesht NWT - YT - NU](https://t.me/MeshtNWT) - <sub><sup>(Telegram)</sup></sub>
- Nova Scotia
  - [Mesht Nova Scotia](https://t.me/MeshtNovaScotia) - <sub><sup>(Telegram)</sup></sub>
- Ontario
  - [Greater Ottawa Meshtastic Enthusiasts](https://discord.com/invite/THXwXWDRyT) - <sub><sup>(Discord)</sup></sub>
  - [GTA+ Meshtastic Community](https://discord.com/invite/snYp3ghCXC) - <sub><sup>(Discord)</sup></sub>
  - [Mesht Ontario](https://t.me/meshtOnt) - <sub><sup>(Telegram)</sup></sub>
- Prince Edward Island
  - [Mesht PEI](https://t.me/MeshtPEI) - <sub><sup>(Telegram)</sup></sub>
- Quebec
  - [Mesht Quebec](https://t.me/meshtQuebec) - <sub><sup>(Telegram)</sup></sub>
- Saskatchewan
  - [Mesht Saskatchewan](https://t.me/MeshtSaska) - <sub><sup>(Telegram)</sup></sub>
  - [Meshtastic Saskatoon](https://www.facebook.com/groups/1870643856678060/) - <sub><sup>(Facebook)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇨🇳China

- [Meshtastic 中国社区](https://meshcn.net)

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇨🇴Colombia

- [Meshtastic Users Colombia](https://t.me/meshtasticco) - <sub><sup>(Telegram)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### Denmark

- [Danske Meshtastic Brugere](https://discord.gg/EXWWwDmfBN)

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇫🇮Finland

- [Mesh Finland](https://discord.com/invite/GHnaVAjqed) - <sub><sup>(Discord)</sup></sub>
- [Mesh Finland](https://mesh-finland.github.io) - <sub><sup>(Website)</sup></sub>
- [MeshAbout](https://www.meshabout.fi/) - <sub><sup>(Discord)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇫🇷France

- [Autour de Meshtastic](https://t.me/+EYBkU17mlcU2MWI8) - <sub><sup>(Telegram)</sup></sub>
- [Collectif Meshtastic France](https://www.facebook.com/groups/meshtastic.france) - <sub><sup>(Facebook)</sup></sub>
- [Réseau Gaulix](https://t.me/+bkCEaiI-i-Q2ZTBk) - <sub><sup>(Telegram)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇩🇪Germany

- [Meshtastic Users D-A-CH](https://t.me/meshtasticgermany) - <sub><sup>(Telegram)</sup></sub>
- [Meshtastic Users Germany](https://www.facebook.com/share/o6CZ9E35UmDKjp9U/) - <sub><sup>(Facebook)</sup></sub>
- [Mesh Hessen](https://meshhessen.de/) - <sub><sup>(Website)</sup></sub>
- [Mesh Hessen](https://t.me/Mesh_Hessen) - <sub><sup>(Telegram)</sup></sub>
- [Meshtastic Users Hannover](https://discord.gg/eEnDkQKEFJ) - <sub><sup>(Discord)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇮🇳India

- [Bir Paragliding Community](https://bircom.in)

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇮🇱Israel

- [Israel Meshtastic Club](https://www.mesh-il.com)

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇮🇹Italy

- [Meshtastic Italia Community](https://t.me/meshtastic_italia_community) - <sub><sup>(Telegram)</sup></sub>
- [Mesh_ITA](https://discord.gg/ETFmtyzbFT) - <sub><sup>(Discord)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇯🇵Japan

- [Meshtastic Japan Community](https://www.facebook.com/share/g/BQCGxZhw9SxFQja8/?mibextid=K35XfP) - <sub><sup>(Facebook)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇱🇻Latvia

- [Meshtastic Latvija](https://mesh.dodies.lv)
- [Meshtastic Latvija Matrix Space](https://matrix.to/#/#meshtastic-lv:matrix.org)

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇱🇹Lithuania

- [Meshtastic Lietuva](https://www.facebook.com/groups/1122509422249414) - <sub><sup>(Facebook)</sup></sub>
- [LithMesh Signal Group](https://signal.group/#CjQKIBScbOkXSG2bkFh_omdxjOM-XqYIU4eERDmGEDrm3jjmEhDyZhh-EeCLSfjfV-DoPvEQ)

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇲🇽Mexico

- [Meshtastic Mexico Community](https://radioaficionados.mx/meshtastic)
- [Meshtastic User Group Mexico (MUG-Mexico)](https://t.me/meshtastic_mexico) - <sub><sup>(Telegram)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇳🇱Netherlands, The

- [Meshtastic Netherlands](https://t.me/meshtastic_nl) - <sub><sup>(Telegram)</sup></sub>
- [MeshNet Meshtastic Community](https://www.meshnet.nl/)

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇳🇿New Zealand

- [New Zealand Meshtastic Community](https://discord.gg/xb9bBZJUpz) - <sub><sup>(Discord)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇵🇱Poland

- [Meshtastic Polska](https://matrix.to/#/#meshtasticpl:matrix.org) - <sub><sup>(Matrix)</sup></sub>
- Warsaw
  - [Meshtastic Warszawa](https://signal.group/#CjQKIH6ht6sTWQDyjV7FMBAU4ko6xHVTRjIp1Eo-q44ZHVxYEhBuR--ztVU0JCa-196WxJmV) - <sub><sup>(Signal)</sup></sub>
  - [Meshtastic Warszawa](https://wiki.868.band/Home) - <sub><sup>(Website)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇸🇮Slovenia

- [MeshNet.si](https://meshnet.si)
- [Slovenian Amateur Radio](https://discord.gg/uHDDE734DD) - <sub><sup>(Discord)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇿🇦South Africa

- [Meshtastic ZA](https://discord.gg/tKGFwFYvsT) - <sub><sup>(Discord)</sup></sub>
- [ZA Mesh](https://mesh.zr1rf.za.net/)

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇪🇸Spain

- [Meshtastic Spanish Community](https://t.me/meshtastic_esp) - <sub><sup>(Telegram)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇸🇪Sweden

- [STHLM-MESH](https://discord.gg/gchSzHkPGG) - <sub><sup>(Discord)</sup></sub>
- [STHLM-MESH](https://sthlm-mesh.se) - <sub><sup>(Website)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇹🇼Taiwan

- [Meshtastic Taiwan Community 臺灣鏈網](https://www.facebook.com/groups/413628121046386) - <sub><sup>(Facebook)</sup></sub>
- [Meshtastic Taiwan Community 臺灣鏈網](https://discord.gg/2vZkuckp8E) - <sub><sup>(Discord)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇹🇷Türkiye

- [Meshtastic Türkiye Community](https://t.me/trmesh) - <sub><sup>(Telegram)</sup></sub>
- [Meshtastic Türkiye Community](https://discord.gg/7TGnZSSA) - <sub><sup>(Discord)</sup></sub>
- ~~Meshtastic Türkiye Community - Web~~ - [Archived](https://web.archive.org/web/20241207225721/http://trmesh.org/)

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇺🇦Ukraine

- ~~WiKi Meshtastic UA~~ - [Archived](https://web.archive.org/web/20241012101501/https://wikimesh.pp.ua/uk/home)

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇬🇧United Kingdom

- [UK Meshtastic Kent / South East](https://www.facebook.com/groups/ukmeshtastickent/) - <sub><sup>(Facebook)</sup></sub>
- [UK Meshtastic Brighton](https://www.facebook.com/groups/3696312513946679/) - <sub><sup>(Facebook)</sup></sub>
- [UK Meshtastic North East England](https://www.facebook.com/groups/meshtasticnortheastengland/) - <sub><sup>(Facebook)</sup></sub>
- [Swansea Meshtastic Group / Meshtastic Wales](https://swansea.localmesh.org/)
- [UK Meshtastic Berkshire](https://www.facebook.com/groups/1083395923209693) - <sub><sup>(Facebook)</sup></sub>

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

### 🇺🇸United States

- [Meshtastic USA Community](https://www.facebook.com/groups/meshtasticusa/) - <sub><sup>(Facebook)</sup></sub>
- [Midwest Mesh](https://discord.gg/wYwD56K439) - <sub><sup>(Discord)</sup></sub>
- [Mountain Mesh (North GA / East TN)](https://mtnme.sh)
- [DMV (DC-MD-VA) Mesh](https://www.reddit.com/r/Meshtastic_DMV_Users/)
- Alabama
  - [Birmingham Mesh](https://birminghammesh.org/)
- Arizona
  - [Tucson Meshtastic Community](https://discord.gg/7MzbMMd2kg) - <sub><sup>(Discord)</sup></sub>
  - [Arizona Meshtastic Community](https://azmsh.net)
- Arkansas
  - [Central Arkansas](https://lrme.sh)
  - [Fort Smith Mesh](https://discord.com/invite/nwsvcXeqMX) - <sub><sup>(Discord)</sup></sub>
- California
  - [SoCal Mesh](https://socalmesh.org)
  - [Laguna Mesh](https://lagunamesh.com)
  - [Mission Viejo Mesh](https://missionviejomesh.org/)
  - [Meshtastic Bay Area Group](https://bayme.sh/)
  - [MontereyBayMesh](https://mrymesh.net/)
  - [San Diego Mesh](https://discord.gg/k8RputgWgD) - <sub><sup>(Discord)</sup></sub>
  - [Antelope Valley Mesh](https://www.avmesh.org/)
  - ~~AltaMesh~~ - [Archived](https://web.archive.org/web/20250122193410/https://altamesh.net/)
  - [Central Valley](https://centralvalleymesh.net/)
  - [Sac Valley Mesh](http://www.sacvalleymesh.com)
  - [Inter-Canyon Mesh - Orange County Canyons](https://icmesh.com)
  - [Meshtastic Santa Cruz County](https://groups.io/g/Meshtastic-Santa-Cruz)
- Colorado
  - [Denver Mesh](https://denvermesh.org)
  - [Colorado Springs Meshtastic Network](https://www.facebook.com/groups/cosmeshtastic) - <sub><sup>(Facebook)</sup></sub>
- Connecticut
  - [CT Mesh](https://ctmesh.org)
- Florida
  - [Space Coast Mesh](https://scmesh.org/)
  - [JAXMesh](https://jaxmesh.com/)
  - [Florida Mesh](https://areyoumeshingwith.us/) - <sub><sup>(Website)</sup></sub>
  - [Florida Mesh](https://github.com/flmesh) - <sub><sup>(Github)</sup></sub>
  - [Florida Mesh](https://discord.com/invite/JUc8N9nUa8) - <sub><sup>(Discord)</sup></sub>
  - [Meshtastic Florida](https://www.reddit.com/r/Meshtastic_Florida/) - <sub><sup>(Reddit)</sup></sub>
- Georgia
  - [CSRA Mesh - Augusta, GA/North Augusta, SC Area](https://discord.gg/rQSTQDZKgs) - <sub><sup>(Discord)</sup></sub>
- Hawaii
  - [Hawaii Meshnet](https://www.hawaiimesh.net/)
- Illinois
  - [Chicagoland Mesh](https://chicagolandmesh.org)
  - [Clark County Illinois Meshtastic Network](https://clarkcountyill.localmesh.org/)
- Iowa
  - [Iowa Mesh](https://iowamesh.org)
- Kansas
  - [SecKC Amateur Radio Club of Kansas City and Surrounding Cities for Amateur Radio](https://ks3ckc.radio/home)
- Maine
  - [Maine Mesh](https://github.com/JFRHorton/MaineMesh)
- Massachusetts
  - [Boston Meshnet](https://github.com/Darachnid/Boston-Meshnet)
  - [SouthCoast Mesh](https://southcoastmesh.com)
- Michigan
  - [Michigan Meshtastic Network](https://discord.gg/3A5RREcBcc) - <sub><sup>(Discord)</sup></sub>
- Missouri
  - [Kansas City Meshtastic Group](https://www.facebook.com/share/XZ9jnhxy1YT4wWqC/) - <sub><sup>(Facebook)</sup></sub>
  - [MeshSTL - St. Louis](https://discord.gg/QYxUdKZpBd) - <sub><sup>(Discord)</sup></sub>
  - [CMRG Mesh - Jefferson City](https://www.mo-mesh.com)
- Nevada
  - [VegasMesh](https://discord.gg/vUmWuZxYPh) - <sub><sup>(Discord)</sup></sub>
- New Hampshire
  - [NHMesh](https://discord.gg/PkbHWSEXBv) - <sub><sup>(Discord)</sup></sub>
- New Mexico
  - [Albuquerque Mesh](https://www.abqm.net)
- North Carolina
  - [North Carolina Mesh](https://ncmesh.net/)
- Ohio
  - [Cincy Mesh](https://www.cincymesh.org)
  - [Dayton Mesh](https://daytonmesh.org/)
  - [Central Ohio (Columbus Metro Area) Mesh](https://meshcolumb.us/)
- Oklahoma
  - [Oklahoma Meshtastic Group](https://www.facebook.com/groups/942404880478488) - <sub><sup>(Facebook)</sup></sub>
- Oregon
  - [Southern Oregon Meshtastic Community](https://sites.google.com/view/someshtastic/home)
  - [PDXMesh for Portland & SW Washington](https://pdxmesh.com)
  - [Willamette Valley Mesh Eugene / Springfield](https://discord.gg/gf4mShtJz4) - <sub><sup>(Discord)</sup></sub>
- Pennsylvania
  - [Philly Radio & Meshtastic](https://discord.gg/MWWbAkRR9v) - <sub><sup>(Discord)</sup></sub>
- Tennessee
  - [Nashville Meshville](https://meshville.org/)
- Texas
  - [Austin Mesh](https://austinmesh.org/) - <sub><sup>(Website)</sup></sub>
  - [Austin Mesh](https://www.instagram.com/austinmesh/) - <sub><sup>(Instagram)</sup></sub>
  - [Austin Mesh](https://discord.com/invite/6a5Sv2s9bG) - <sub><sup>(Discord)</sup></sub>
  - [Austin Mesh](https://www.youtube.com/@austinmesh) - <sub><sup>(YouTube)</sup></sub>
  - [Cypress, Texas Meshtastic Club](https://discord.gg/KzuwNRwE6q) - <sub><sup>(Discord)</sup></sub>
  - [DFW / North Texas Mesh (NTX Mesh)](https://ntxmesh.com/) - <sub><sup>(Website)</sup></sub>
  - [DFW / North Texas Mesh (NTX Mesh)](https://discord.com/invite/nGeQ8cbSM3) - <sub><sup>(Discord)</sup></sub>
- Virginia
  - [MadisonMesh](https://madisonmesh.com/)
  - [Albemarle Mesh](https://albemarlemesh.com/)
  - ~~Shenandoah Valley Mesh~~ - [Archived](https://web.archive.org/web/20250216025925/https://svmesh.org/)
  - [Northern Virginia Meshtastic](https://groups.io/g/NoVa-Meshtastic)
- Wisconsin
  - [Meshconsin](https://meshconsin.org)
- Washington
  - [Puget Mesh](https://pugetmesh.org)
  - [Tacoma.localmesh](https://tacoma.localmesh.org)
- Washington DC
  - [DC Mesh](https://dcmesh.org)

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

## 🤝Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

## 📝License

This Awesome Meshtastic List is licensed under the [Creative Commons Zero (CC0) 1.0 Universal License](https://creativecommons.org/publicdomain/zero/1.0/).

You are free to copy, modify, and distribute this list, even for commercial purposes, without asking permission.

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>

## ⚖️Legal Notice

Meshtastic&reg; is a registered trademark of Meshtastic LLC. This project is in no way affiliated with, endorsed, or sponsored by the trademark holder. No infringement is intended.

<sup>[🔝](#table-of-contents) [Table of Contents](#table-of-contents) [🔝](#table-of-contents)</sup>
