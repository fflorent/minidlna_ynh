<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# MiniDLNA for YunoHost

[![Integration level](https://dash.yunohost.org/integration/minidlna.svg)](https://dash.yunohost.org/appci/app/minidlna) ![](https://ci-apps.yunohost.org/ci/badges/minidlna.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/minidlna.maintain.svg)  
[![Install MiniDLNA with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=minidlna)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install MiniDLNA quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

MiniDLNA is a simple media server software, with the aim of being fully compliant with DLNA/UPnP-AV clients.


**Shipped version:** 1.0~ynh8



## Disclaimers / important information

## Configuration

Edit the file `/etc/minidlna.conf` to adjust the configuration of MiniDLNA.

## YunoHost specific features

* Use shared Multimedia Directories
* Linked to transmission, Nextcloud and all other app which use Multimedia Directories.

## Documentation and resources

* Official app website: http://minidlna.sourceforge.net
* YunoHost documentation for this app: https://yunohost.org/app_minidlna
* Report a bug: https://github.com/YunoHost-Apps/minidlna_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --debug
or
sudo yunohost app upgrade minidlna -u https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps