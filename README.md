# Mumble server for YunoHost

[![Integration level](https://dash.yunohost.org/integration/mumbleserver.svg)](https://dash.yunohost.org/appci/app/mumbleserver) ![](https://ci-apps.yunohost.org/ci/badges/mumbleserver.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mumbleserver.maintain.svg)  
[![Install Mumble Server with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=mumbleserver)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Mumble Server quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Quick description of this app.

**Shipped version:** 1.3.0 (source package provided by Debian) 

## Screenshots

![](Link to a screenshot of this app.)

## Demo

* [Official demo](Link to a demo site for this app.)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.
- [Add the admin](http://wiki.mumble.info/wiki/Murmurguide#Connecting_to_Murmur_Server)

Password and other usefull information will be sent to you after installation.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/mumbleserver%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/mumbleserver/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/mumbleserver%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/mumbleserver/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug about this package: https://github.com/YunoHost-Apps/mumbleserver_ynh
 * Report a bug about Mumble itself: https://github.com/mumble-voip/mumble
 * Mumble website: https://mumble.info
 * YunoHost website: https://yunohost.org

 ---

## Developer info

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/mumbleserver_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mumbleserver_ynh/tree/testing --debug
or
sudo yunohost app upgrade mumbleserver -u https://github.com/YunoHost-Apps/mumbleserver_ynh/tree/testing --debug
```
