<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Vikunja for YunoHost

[![Integration level](https://dash.yunohost.org/integration/vikunja.svg)](https://dash.yunohost.org/appci/app/vikunja) ![Working status](https://ci-apps.yunohost.org/ci/badges/vikunja.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/vikunja.maintain.svg)

[![Install Vikunja with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=vikunja)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Vikunja quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Vikunja is a self-hosted open-source to-do list application for all platforms.

### Features

- Stay organized 
- Collaborate with peers
- Tasks  
- Kanban board
- CalDAV
- Links  

**Shipped version:** 0.21.0~ynh3

**Demo:** https://try.vikunja.io/login

## Screenshots

![Screenshot of Vikunja](./doc/screenshots/kanban.png)

## Documentation and resources

* Official app website: <https://vikunja.io/>
* Official admin documentation: <https://vikunja.io/docs/>
* Upstream app code repository: <https://kolaente.dev/vikunja/>
* Report a bug: <https://github.com/YunoHost-Apps/vikunja_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing --debug
or
sudo yunohost app upgrade vikunja -u https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
