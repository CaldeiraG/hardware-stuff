# Homelab

#### (updated at 2025-01-20)

## [Intel® NUC 10 Performance - NUC10i7FNHAA](https://www.intel.com/content/www/us/en/products/sku/188813/intel-nuc-10-performance-mini-pc-nuc10i7fnhaa/specifications.html)

CPU: Intel® Core™ i7-10710U @ up to 4.7Ghz

RAM: 2x16GB SODIMM DDR4-2666 @ 2666Mhz

GPU: Intel® UHD Graphics

SDD: 1TB WD Black SN770

SO: Proxmox 8

It runs 10 VM's:

#### 101 - Paperless-ngx CT

#### 102 - QBitTorrent

#### 105 - Home Assistant VM

#### 111 - MQTT Mosquitto LXC

#### 112 - Mediaserver DBs LXC

#### 113 - PostgresDB LXC

#### 114 - AdGuardHome LXC

#### 116 - Unifi Controller LXC

#### 118 - Plex VM

## [Dell Optiplex 3080 Mini](https://www.dell.com/support/manuals/en-us/optiplex-3080-micro/optiplex3080_micro_specs/technical-specifications?guid=guid-26cc9b57-795f-4689-8649-667d70d1f3bd&lang=en-us)

CPU: Intel i5-10500T @ 2.30 GHz

RAM: 2x16GB SODIMM DDR4-2666T @ 2666Mhz

GPU: Intel® UHD Graphics

SDD: 250gb Teamgroup SSD (local) / 1tb Samsung 970 Evo Plus (samgirl-fast)

SO: Proxmox 8

#### 100 - Immich CT

#### 104 - Windows 11 VM

#### 108 - AdGuardHome

#### 115 - Mediaserver apps

- Jellyfin

- Sonarr

- Radarr

- Jackett

- Tautulli

- Qbittorrent

- Bazarr

- Lidarr


#### 117 - Ubuntu VM - runs most of the other selfhosted apps (Docker)

- RedLib
- Actual
- Wg-Easy
- Scrutiny
- Radicale
- AdGuardHome


#### 120 - Zigbee2MQTT

## Raspberry Pi Zero 2W

Not sure what to do with this one atm

## ASUSTOR AS6102T - 2x12TB Seagate Exos - Mediaserver Storage

## Network

- 2x Unifi U6-Lite
- Zyxel EX3301-T0 as main fiber router for the moment
- Asus AX56U running on AP mode
- USW-Lite-8-POE powers the homelab, one of the U6-Lites and the PC

## Previous devices
- Lenovo Thinkcentre M700 Tiny
- Raspberry Pi 4B 4GB