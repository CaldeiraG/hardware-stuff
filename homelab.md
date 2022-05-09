# Homelab

#### (updated at 2022-05-09)

## Lenovo ThinkCentre M700 Tiny

CPU: Intel i5-6400T @ 2.70 GHz

RAM: 2x16GB SODIMM DDR4-2400T @ 2400Mhz

GPU: integrated

SDD: 500gb WD Blue boot drive (local/local-lvm) / 250gb 850 Evo (samgirl) for VM storage

HDD: External 2Tb Seagate Drive (media server)

SO: Proxmox 7

It runs 8 VM's:

#### 101 - Zigbee2mqtt LXC

#### 102 - Windows 11

#### 104 - Ubuntu LXC (media server)

- Plex

- Jellyfin

- Sonarr

- Radarr

- Jackett

- Tautulli

- Qbittorrent

- Bazarr

- Lidarr

#### 105 - Home Assistant OS

#### 106 - Ubuntu LXC - runs most of the other selfhosted apps (Docker)

- Pi-Alert

- Bookstack

- YoutubeDL-Material

- AdGuardHome-sync

- Scrutiny

- Snipe-it

- Exportarr

- Watchtower

- Openspeedtest

- Speedtest-tracker

- Cloudflare-DDNS

- Firefly-III

- Paperless-ngx

- Grafana

- Portainer

#### 107 - PopOS VM

#### 108 - macOS VM

#### 109 - Reverse Proxy LXC

- Nginx Proxy Manager

- Authentik

- Vaultwarden

#### 110 - Unifi Controller LXC

#### 111 - MQTT Mosquitto LXC

#### 112 - Fedora Workstation 35 VM

#### 113 - AdGuardHome LXC

![Proxmox overview](https://eu2.contabostorage.com/4acdd888060f42c3822d59f568b40046:calcdn/ShareX/2022/05/vivaldi_mzS9yuGHiY.png)

## Raspberry Pi 4B - 4GB RAM

- Secondary AdGuardHome instance

- Other random stuff 

## Raspberry Pi Zero 2W - 512MB RAM

Not sure what to do with this one atm

## ASUSTOR AS6102T - 2x12TB Seagate Exos

This will eventually replace the 2TB drive and become the main storage server for the media server. It will most likely run as RAID 0 so I get the most out of it and video files or generally available series is not a concern if I lose it. These will probably last long enough and if I ever need more storage a bigger NAS (or a dedicated storage server) will overcome it

## Network In progress

- 2x Unifi U6-Lite
- Asus AX56U as replacement for ISP router with AsusWRT-Merlin
- USW-Lite-8-POE powers the homelab, one of the U6-Lites and the PC
