# IDX Theme

An [IDX](https://idx.google.com/) inspired Theme for Home Assistant.

[![GitHub Release](https://img.shields.io/github/v/release/veniplex/hass-idx-theme?label=Version&link=https%3A%2F%2Fgithub.com%2Fveniplex%2Fhass-idx-theme%2Freleases)](https://github.com/veniplex/hass-idx-theme/releases)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/veniplex/hass-idx-theme/total?label=Downloads&link=https%3A%2F%2Fgithub.com%2Fveniplex%2Fhass-idx-theme%2Freleases)](https://github.com/veniplex/hass-idx-theme/releases)
[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/veniplex/hass-idx-theme/validate.yaml?label=HACS%20Validation&link=https%3A%2F%2Fgithub.com%2Fhacs%2Faction)](https://github.com/hacs/action)

![IDX Preview Image](https://github.com/veniplex/hass-idx-theme/blob/main/assets/IDX_Preview.png)

## Supported Integrations

| Name | Status |
| - | - |
| [Lovelace Vacuum Map Card](https://github.com/PiotrMachowski/lovelace-xiaomi-vacuum-map-card) by [PiotrMachowski](https://github.com/PiotrMachowski) </br> <details><summary>Preview</summary><img width=250 src="https://github.com/veniplex/hass-idx-theme/assets/lovelace-xiaomi-vacuum-map-card_light.png" alt="Preview Lovelace Vacuum Map Card Light" /><img width=250 src="https://github.com/veniplex/hass-idx-theme/assets/lovelace-xiaomi-vacuum-map-card_dark.png" alt="Preview Lovelace Vacuum Map Card Dark" /></details> | :ballot_box_with_check: (Partial) |
| [Vacuum Card](https://github.com/denysdovhan/vacuum-card) by [denysdovhan](https://github.com/denysdovhan) </br> <details><summary>Preview</summary><img width=250 src="https://github.com/veniplex/hass-idx-theme/assets/vacuum-card_light.png" alt="Preview Vacuum Card Light" /><img width=250 src="https://github.com/veniplex/hass-idx-theme/assets/vacuum-card_dark.png" alt="Preview Vacuum Card Dark" /></details> | :white_check_mark: (Full) |

## Installation

### Install via Home Assistant Community Store (HACS)

[![Open your Home Assistant instance and open this repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=veniplex&repository=hass-idx-theme&category=theme)

IDX Theme is available in [HACS (Home Assistant Community Store)](https://hacs.xyz/).

1. Open HACS
2. Go to "Frontend" section
3. Click the three dots in the top right corner.
4. Select "Custom Repository".
5. Paste the link to this repository in the "Repository" field `https://github.com/veniplex/hass-idx-theme`.
6. As "Category" select "Theme".
7. Click "Add".

### Install manually

Add the following code to your `configuration.yaml` file (restart required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

## Features & Bugs

If you find a bug, if you are missing anything or if you have a suggestion for improvment, please let me know via an [Issue](https://github.com/veniplex/hass-idx-theme/issues).

## Sponsor this project

<a href="https://www.buymeacoffee.com/veniplex" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height=50 ></a>
<a href="https://www.patreon.com/bePatron?u=135604640"><img src="https://github.com/veniplex/veniplex/blob/main/Support-Me-On-Patreon.svg" height=50 /></a>

<p align="center">Made with <a href="https://wikipedia.org/wiki/Love"><img src="https://api.iconify.design/heroicons-solid:heart.svg?color=%23ff0000" /></a> by <a href="https://github.com/veniplex">@veniplex</a></p>