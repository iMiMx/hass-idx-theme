# IDX Theme

An [IDX](https://idx.google.com/) inspired Theme for Home Assistant.

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
