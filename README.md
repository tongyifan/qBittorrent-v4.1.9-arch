# qBittorrent v4.1.9 PKGBUILDs
Revised PKGBUILDs of libtorrent-rasterbar v1.1 and qBittorrent v4.1.9, for Arch/Manjaro Linux.

## Usage
1. `cd libtorrent-rasterbar` , then `makepkg -i`
2. `cd qbittorrent` , then `makepkg -i`
3. edit `/etc/pacman.conf` , add these packages into `IgnorePkg`
   - qbittorrent
   - qbittorrent-nox
   - libtorrent-rasterbar-1_1-git

## Sources
- [qBittorrent v4.1.9 official PKGBUILD](https://github.com/archlinux/svntogit-community/blob/5c4c9f8996b6f643c6ce15bb3d46a0d60f37db18/trunk/PKGBUILD)
- [libtorrent-rasterbar v1.1 AUR PKGBUILD from Chocobo1](https://aur.archlinux.org/cgit/aur.git/tree/PKGBUILD?h=libtorrent-rasterbar-1_1-git)
