# Homelab

#### (updated at 2022-02-21)

## Lenovo ThinkCentre M700 Tiny

CPU: Intel i5-6400 @ 2.70 GHz

RAM: 2x16GB SODIMM DDR4-2400T @ 2400Mhz

GPU: integrated

SDD: 500gb WD Blue boot drive (local/local-lvm) / 250gb 850 Evo (samgirl) for VM storage

HDD: External 2Tb Seagate Drive (media server)

SO: Proxmox 7

It runs 8 VM's:

#### 100 - Ubuntu LXC (media server)

- Plex

- Jellyfin

- Sonarr

- Radarr

- Jackett

- Tautulli

- Qbittorrent

#### 101 - OMV

#### 102 - Windows 11

#### 103 - Kasm LXC

#### 105 - Ubuntu Testing Server LXC

#### 106 - Ubuntu LXC - runs most of the other selfhosted apps (Docker)

- Pi-Hole

- Pi-Alert

- Bookstack

- Firefly-III

- Paperless-ng

- Grafana

- Portainer

- Other random stuff I can't recall

#### 107 - PopOS VM

#### 108 - macOS VM

![Proxmox overview](https://cdn.caldeirag.xyz/hOli8/LuMAmaGU03.png/raw)

## Raspberry Pi 4B - 4GB RAM

- Secondary Pi-Hole instance

- Other random stuff 

## Raspberry Pi Zero 2W - 512MB RAM

Running AdGuardHome at cousin's place while moving is still underway.

## ASUSTOR AS6102T - 2x12TB Seagate Exos (soon™)

This will eventually replace the 2TB drive and become the main storage server for the media server. It will most likely run as RAID 0 so I get the most out of it and video files or generally available series is not a concern if I lose it. These will probably last long enough and if I ever need more storage a bigger NAS (or a dedicated storage server) will overcome it
