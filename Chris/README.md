# Chris's NAS

- [Chris's NAS](#chriss-nas)
  - [Hardware](#hardware)
  - [Installations](#installations)
    - [Want to Add](#want-to-add)
  - [Configurations](#configurations)

## Hardware

| Hardware | Quantity | Product Link | Other Links |
| :------- | :------- | :----------- | :---------- |
| Synology NAS DS920+ | 1 | [DS920+](https://www.synology.com/en-us/products/DS920+) | [Documents](https://www.synology.com/en-us/support/download/DS920+#docs) <br/> [Hardware](https://global.download.synology.com/download/Document/Hardware/HIG/DiskStation/20-year/DS920+/enu/Syno_HIG_DS920_Plus_enu.pdf) |
| Western Digital 8TB WD Red Pro | 2 | [Western Digital](https://shop.westerndigital.com/products/internal-drives/wd-red-pro-sata-hdd#WD8003FFBX) | [Amazon](https://www.amazon.com/Western-Digital-Internal-Hard-Drive/dp/B07D3N95GS?th=1) |
| Samsung 16GB RAM | 1 | [Samsung 16 GB RAM](https://www.newegg.com/samsung-16gb-260-pin-ddr4-so-dimm/p/1B4-001D-005D9) | [Reddit Thread](https://www.reddit.com/r/synology/comments/goidix/good_news_ds920_supports_16gb_ddr4_ram_for_20gb/) |

## Installations

| Application | Installation | Link |
| :---------- | :----------- | :--- |
| Antivirus Essentials | Package Center | N/A |
| Audio Station | Package Center | N/A |
| Calibre | Docker | [Setup]() |
| Cloud Backup | Package Center | [Setup](/Chris/Installations/CloudBackup.md) |
| Docker | Package Center | N/A |
| File Station | Package Center | N/A |
| Hyper Backup | Package Center | N/A |
| Moments | Package Center | [Setup](/Chris/Installations/Photos.md) |
| Plex Media Server | Package Center | [Setup](/Chris/Installations/Plex.md) |
| Photo Station | Package Center | [Setup](/Chris/Installations/Photos.md) |
| Synology Drive | Package Center | N/A |
| USB Copy | Package Center | N/A |

### Want to Add

- Backups for windows machine and mac
- Pi hole
- Transmission through VPN (NordVPN)
  - [Image](https://github.com/haugene/docker-transmission-openvpn)
- Comics
  - Add Comics metadata plugin for Calibre
  - Ubooquity
    - [Image](https://hub.docker.com/r/linuxserver/ubooquity)
  - Komga
    - [Repo](https://github.com/gotson/komga)
- VPN
  - Need to add docs
- Backblaze Backup
- Audiobook setup
  - [Link](https://forums.plex.tv/t/audiobook-guide/205963/3)
  - [Link](https://forums.plex.tv/t/how-do-i-set-up-files-etc-for-audiobooks-in-plex/530837/4)
  - [Link](https://9to5mac.com/2020/09/06/plex-audiobooks/)
  - Tools
    - [Audiobook Builder](https://www.splasm.com/audiobookbuilder/)
    - [Kid3](https://kid3.kde.org/)

## Configurations

| Configuration | Link |
| :------------ | :--- |
| Calibre | [Setup]() |
| Plex | [Setup](/Chris/Installations/Plex.md) |
| Synology DDNS | [Configuration](/Chris/Configurations/SynologyDDNS.md) |