qBittorrent Enhanced Edition
------------------------------------------
[Important Note for user and tracker operators](NOTE.md)
********************************
# Features:
1. Auto Ban Xunlei, QQ, Baidu, Xfplay, DLBT and Offline downloader

2. _Auto Ban Unknown Peer from China_ Option (Default: OFF)

3. Auto Update Public Trackers List (Default: OFF)

4. Auto Ban BitTorrent Media Player Peer Option (Default: OFF)

5. Peer whitelist/blacklist
********************************
### Description:
qBittorrent is a bittorrent client programmed in C++ / Qt that uses
libtorrent (sometimes called libtorrent-rasterbar) by Arvid Norberg.

It aims to be a good alternative to all other bittorrent clients
out there. qBittorrent is fast, stable and provides unicode
support as well as many features.

The free [IP to Country Lite database](https://db-ip.com/db/download/ip-to-country-lite) by [DB-IP](https://db-ip.com/) is used for resolving the countries of peers. The database is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

### Installation:
For installation, follow the instructions from INSTALL file, but simple:

```
./configure
make && make install
qbittorrent
```

will install and execute qBittorrent hopefully without any problem.

## Repository

If you are using a desktop Linux distribution without any special demands, you can use AppImage from release page.

Latest AppImage download: [qBittorrent-Enhanced-Edition-x86_64.AppImage](https://github.com/c0re100/qBittorrent-Enhanced-Edition/releases/latest/download/qBittorrent-Enhanced-Edition-x86_64.AppImage)

#### Arch Linux (Maintainer: [c0re100](https://github.com/c0re100))

[AUR](https://aur.archlinux.org/packages/qbittorrent-enhanced-git/)

[nox AUR](https://aur.archlinux.org/packages/qbittorrent-enhanced-nox-git/)

#### Debian (Maintainer: [Kolcha](https://github.com/Kolcha))

##### Qt5 variants (Debian 11 and above):

[GUI](https://software.opensuse.org//download.html?project=home%3Anikoneko%3Atest&package=qbittorrent-enhanced)

[nox](https://software.opensuse.org//download.html?project=home%3Anikoneko%3Atest&package=qbittorrent-enhanced-nox)

##### Qt6 variants (Debian Testing and above):

[GUI](https://software.opensuse.org//download.html?project=home%3Anikoneko%3Atest&package=qbittorrent-enhanced-qt6)

[nox](https://software.opensuse.org//download.html?project=home%3Anikoneko%3Atest&package=qbittorrent-enhanced-nox-qt6)

The one [repository](https://build.opensuse.org/project/show/home:nikoneko:test) contains all 4 variants listed above, links to specific packages are provided for convenience.

#### openSUSE/RPM-based Linux distro (Maintainer: [PhoenixEmik](https://github.com/PhoenixEmik))

[openSUSE repo](https://build.opensuse.org/package/show/home:PhoenixEmik/qbittorrent-enhanced-edition)

#### Ubuntu (Maintainer: [poplite](https://github.com/poplite))

[PPA](https://launchpad.net/~poplite/+archive/ubuntu/qbittorrent-enhanced)

#### macOS (Homebrew) (Maintainer: [AlexaraWu](https://github.com/AlexaraWu))
```
brew install c0re100-qbittorrent
```

#### Windows

Windows 10 & 11 (Maintainer: [c0re100](https://github.com/c0re100))

```
winget install c0re100.qBittorrent-Enhanced-Edition
```

Chocolatey (Maintainer: [iYato](https://github.com/iYato))

```
choco install qbittorrent-enhanced
```

Scoop

```
scoop bucket add extras
scoop install qbittorrent-enhanced
```

### Misc:
For more information please visit:
https://www.qbittorrent.org

or our wiki here:
http://wiki.qbittorrent.org

Use the forum for troubleshooting before reporting bugs:
http://forum.qbittorrent.org

Please report any bug (or feature request) to:
http://bugs.qbittorrent.org

For enhanced features bug(such as Auto Ban, API, Auto Update Tracker lists...), please report to:
https://github.com/c0re100/qBittorrent-Enhanced-Edition/issues
trigger
