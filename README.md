<!-- This file is generated from docs/readme.en.template.md. Run scripts/build-readme.sh to regenerate. -->

# aur-auto

[![AUR Maintainer](https://img.shields.io/badge/AUR-SlotSun-1793D1?logo=arch-linux&logoColor=white)](https://aur.archlinux.org/packages?SeB=m&K=SlotSun)

Automation toolkit for maintaining Arch User Repository packages with GitHub Actions.

## Overview
- Detect upstream releases per package by calling dedicated hooks in `pkgs/<pkgname>/upstream.sh`.
- Regenerate PKGBUILD metadata, build packages in clean chroots, and publish to AUR.
- Provide bilingual documentation for contributors and maintainers.

## Maintainers
- SlotSun `<slot_sun@outlook.com>`

## Documentation
- Repository Guidelines: [English](docs/guidelines.en.md) | [简体中文](docs/guidelines.zh.md)
- Packaging Workflow: [English](docs/packaging.en.md) | [简体中文](docs/packaging.zh.md)
- README: [English](README.md) | [简体中文](README.zh.md)

## Packages
| Package | Description | Upstream | Version | Build Status |
| --- | --- | --- | --- | --- |
| `slive` | 基于Flutter的聚合直播软件，支持多平台直播源聚合与观看。 | `slive` | 1.8.5 | [![Build Status](https://img.shields.io/github/actions/workflow/status/SlotSun/aur-auto/build-and-publish.yml?branch=main&logo=github&label=build)](https://github.com/SlotSun/aur-auto/actions/workflows/build-and-publish.yml) |
| `slive-bin` | 基于Flutter的聚合直播软件，支持多平台直播源聚合与观看。 | `slive-bin` | 1.8.5 | [![Build Status](https://img.shields.io/github/actions/workflow/status/SlotSun/aur-auto/build-and-publish.yml?branch=main&logo=github&label=build)](https://github.com/SlotSun/aur-auto/actions/workflows/build-and-publish.yml) |
| `unibarrage-bin` | High-performance real-time proxy tool to unify live barrage data collection across multiple streaming platforms | `unibarrage` | 1.0.1 | [![Build Status](https://img.shields.io/github/actions/workflow/status/SlotSun/aur-auto/build-and-publish.yml?branch=main&logo=github&label=build)](https://github.com/SlotSun/aur-auto/actions/workflows/build-and-publish.yml) |

Regenerate this README after documentation or metadata changes with `scripts/build-readme.sh`.
