<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Mobilizon for YunoHost

[![Integration level](https://dash.yunohost.org/integration/mobilizon.svg)](https://dash.yunohost.org/appci/app/mobilizon) ![Working status](https://ci-apps.yunohost.org/ci/badges/mobilizon.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/mobilizon.maintain.svg)  
[![Install Mobilizon with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mobilizon)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Mobilizon quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A decentralized and federated platform to organize events

- Mobilizon is a tool that helps you find, create and organize events.

- You can also create a page for your group where the members will be able to get organized together.



**Shipped version:** 2.1.0.1~ynh5

**Demo:** https://demo.mobilizon.org

## Screenshots

![Screenshot of Mobilizon](./doc/screenshots/screenshot1.jpg)

## Disclaimers / important information

* **Mobilizon** require a dedicated **root domain**, eg. mobilizon.domain.tld
* To connect as **Mobilizon** administrator, use the email address and password of the user you choose during install
* By default registrations are closed
* All YunoHost users are allowed to connect

* Configuration can be made in the Mobilizon administration panel.

## Documentation and resources

* Official app website: <https://joinmobilizon.org/>
* Official user documentation: <https://docs.joinmobilizon.org>
* Upstream app code repository: <https://framagit.org/framasoft/mobilizon/>
* YunoHost documentation for this app: <https://yunohost.org/app_mobilizon>
* Report a bug: <https://github.com/YunoHost-Apps/mobilizon_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/mobilizon_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/mobilizon_ynh/tree/testing --debug
or
sudo yunohost app upgrade mobilizon -u https://github.com/YunoHost-Apps/mobilizon_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
