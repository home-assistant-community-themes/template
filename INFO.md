# Template Theme

[![Build Status](https://www.travis-ci.org/home-assistant-community-themes/template.svg?branch=master)](https://www.travis-ci.org/home-assistant-community-themes/template)
[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/custom-components/hacs)

<a href="https://www.buymeacoffee.com/maartenpaauw" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

> The Template Theme by Maarten Paauw

## Screenshots

![Template Theme](https://raw.githubusercontent.com/home-assistant-community-themes/template/master/docs/template-overview.png)

## Installation

1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

2. Go to the Community Store.
3. Search for `Template`.
4. Navigate to `Template` theme.
5. Press `Install`.
6. Restart Home Assistant to make it show up.
