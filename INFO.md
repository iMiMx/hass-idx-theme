# IDX Theme

An [IDX](https://idx.google.com/) inspired Theme for Home Assistant.

## Installation

Add the following code to your `configuration.yaml` file (restart required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```
### HACS
Mushroom Themes is available in [HACS (Home Assistant Community Store)](https://hacs.xyz/).

1. Open HACS
2. Go to "Frontend" section
3. Click the "+" icon
4. Search for "IDX"