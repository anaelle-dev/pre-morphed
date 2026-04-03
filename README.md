#### ⚠️ Do not download APKs or modules from random websites you find on Google, as they may be dangerous and because providers impersonate ReVanced/ReVanced Extended/Morphe. Please build your application from official sources or use open source builders like this one.

# Welcome to my ReVanced/Morphe Builder!
[![CI](https://github.com/anaelle-dev/pre-morphed/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/anaelle-dev/pre-morphed/actions/workflows/ci.yml)
[![GitHub License](https://img.shields.io/github/license/peternmuller/revanced-morphe-builder?logo=gnu&label=License&link=https%3A%2F%2Fgithub.com%2Fpeternmuller%2Frevanced-morphe-builder%2Fblob%2Fmain%2FLICENSE)](https://github.com/peternmuller/revanced-morphe-builder/blob/main/LICENSE)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/anaelle-dev/pre-morphed/total?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48cGF0aCBkPSJNNC43NSAxNy4yNWEuNzUuNzUgMCAwIDEgLjc1Ljc1djIuMjVjMCAuMTM4LjExMi4yNS4yNS4yNWgxMi41YS4yNS4yNSAwIDAgMCAuMjUtLjI1VjE4YS43NS43NSAwIDAgMSAxLjUgMHYyLjI1QTEuNzUgMS43NSAwIDAgMSAxOC4yNSAyMkg1Ljc1QTEuNzUgMS43NSAwIDAgMSA0IDIwLjI1VjE4YS43NS43NSAwIDAgMSAuNzUtLjc1WiIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPjxwYXRoIGQ9Ik01LjIyIDkuOTdhLjc0OS43NDkgMCAwIDEgMS4wNiAwbDQuOTcgNC45NjlWMi43NWEuNzUuNzUgMCAwIDEgMS41IDB2MTIuMTg5bDQuOTctNC45NjlhLjc0OS43NDkgMCAxIDEgMS4wNiAxLjA2bC02LjI1IDYuMjVhLjc0OS43NDkgMCAwIDEtMS4wNiAwbC02LjI1LTYuMjVhLjc0OS43NDkgMCAwIDEgMC0xLjA2WiIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPjwvc3ZnPg==&label=Downloads&link=https%3A%2F%2Fgithub.com%2Fanaelle-dev%2Fpre-morphed%2Freleases)](https://github.com/anaelle-dev/pre-morphed/releases)

This Morphe builder creates both APKs and [Magisk](https://github.com/topjohnwu/Magisk)/[KernelSU](https://github.com/tiann/KernelSU) modules for [Morphe](https://github.com/MorpheApp) versions of YouTube and YouTube Music.

#### **Get the latest CI release [here](https://github.com/anaelle-dev/pre-morphed/releases/latest)!**

## Installation
### Non-root users
- Install [MicroG-RE](https://github.com/MorpheApp/MicroG-RE/releases/latest).
- Download the APK files you want to install from the [releases page](https://github.com/anaelle-dev/pre-morphed/releases/latest), or follow the installation steps [here](https://github.com/anaelle-dev/pre-morphed?tab=readme-ov-file#easily-install-or-update-revancedmorphe-apps-with-obtainium).
- Enjoy!
### Root users
- Download the ZIP files you want to flash from the [releases page](https://github.com/anaelle-dev/pre-morphed/releases/latest).
- (Optional) Use [zygisk-detach](https://github.com/j-hc/zygisk-detach) to detach YouTube and YouTube Music from the Play Store.
- Enjoy!

## Easily install or update Morphe apps with Obtainium
You can easily install or keep your Morphe apps up to date by using [Obtainium](https://github.com/ImranR98/Obtainium), which lets you install and update apps directly from the source and receive notifications when new releases are available.

#### Here is a quick tutorial on how to add them to Obtainium:

<img width="2160" alt="obtainium_quick_tutorial" src="https://github.com/user-attachments/assets/345e0536-529e-4f64-8b0b-ab44ca9e285d">

> [!NOTE]
> In step 3, you need to enter the regular expression that corresponds to the application you want to install:
> - YouTube Morphe: `youtube-morphe`
> - YouTube Music Morphe: `yt-music-morphe`

## If you are having trouble with the classic mount method of the modules
such as,
- **"Reflash needed"** error after reboots
- **"Suspicious mount detected"** warnings from root detector apps

You can consider using [rvmm-zygisk-mount](https://github.com/j-hc/rvmm-zygisk-mount)

## Building Locally
### On Termux
```bash
bash <(curl -sSf https://raw.githubusercontent.com/anaelle-dev/pre-morphed/main/build-termux.sh)
```
### On Linux
```bash
git clone https://github.com/anaelle-dev/pre-morphed --depth 1
cd pre-morphed
./build.sh
```

## Credits
- [j-hc](https://github.com/j-hc) and [peternmuller](https://github.com/peternmuller) for creating this amazing builder.
- [Kevinr99089](https://github.com/kevinr99089) for providing assistance with the builder.
- And of course, the [ReVanced](https://github.com/ReVanced) team, [anddea](https://github.com/anddea), and the [Morphe](https://github.com/MorpheApp) team for their work on the ReVanced/Morphe apps!

## License
    Copyright (C) 2024-2026  Peter Noël Muller

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program. If not, see <https://www.gnu.org/licenses/>.
