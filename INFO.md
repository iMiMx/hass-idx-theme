# IDX Theme

An [IDX](https://idx.google.com/) inspired Theme for Home Assistant.

[![GitHub Release](https://img.shields.io/github/v/release/veniplex/hass-idx-theme?label=Version&link=https%3A%2F%2Fgithub.com%2Fveniplex%2Fhass-idx-theme%2Freleases)](https://github.com/veniplex/hass-idx-theme/releases)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/veniplex/hass-idx-theme/total?label=Downloads&link=https%3A%2F%2Fgithub.com%2Fveniplex%2Fhass-idx-theme%2Freleases)](https://github.com/veniplex/hass-idx-theme/releases)
[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/veniplex/hass-idx-theme/validate.yaml?label=HACS%20Validation&link=https%3A%2F%2Fgithub.com%2Fhacs%2Faction)](https://github.com/hacs/action)

![IDX Preview Image](https://github.com/veniplex/hass-idx-theme/blob/main/assets/IDX_Preview.png)

## Installation

### HACS

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=veniplex&repository=hass-idx-theme&category=theme)

IDX Theme is available in [HACS (Home Assistant Community Store)](https://hacs.xyz/).

1. Open HACS
2. Go to "Frontend" section
3. Click the three dots in the top right corner.
4. Select "Custom Repository".
5. Paste the link to this repository in the "Repository" field `https://github.com/veniplex/hass-idx-theme`.
6. As "Category" select "Theme".
7. Click "Add".

### Manual

Add the following code to your `configuration.yaml` file (restart required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```
