<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Zola for YunoHost

[![Integration level](https://dash.yunohost.org/integration/zola.svg)](https://dash.yunohost.org/appci/app/zola) ![Working status](https://ci-apps.yunohost.org/ci/badges/zola.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/zola.maintain.svg)

[![Install Zola with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zola)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Zola quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Zola is a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator).

With this package, Zola will automatically regenerate ([using Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) your website if any change is made to your sources.


**Shipped version:** 0.18.0~ynh4

## Screenshots

![Screenshot of Zola](./doc/screenshots/zola-screenshot.jpg)

## Documentation and resources

- Official app website: <https://www.getzola.org/>
- Official admin documentation: <https://www.getzola.org/documentation/getting-started/overview/>
- Upstream app code repository: <https://github.com/getzola/zola>
- YunoHost Store: <https://apps.yunohost.org/app/zola>
- Report a bug: <https://github.com/YunoHost-Apps/zola_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/zola_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
or
sudo yunohost app upgrade zola -u https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
