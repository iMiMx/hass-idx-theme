# IDX Theme

An [IDX](https://idx.google.com/) inspired Theme for Home Assistant.

## Installation

### HACS

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=veniplex&category=theme&repository=https%3A%2F%2Fgithub.com%2Fveniplex%2Fhass-idx-theme)

IDX Theme is available in [HACS (Home Assistant Community Store)](https://hacs.xyz/).

1. Open HACS
2. Go to "Frontend" section
3. Click the "+" icon
4. Search for "IDX"

### Manual

Add the following code to your `configuration.yaml` file (restart required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```