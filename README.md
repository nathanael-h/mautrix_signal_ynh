<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# Matrix Signal bridge for YunoHost

[![Integration level](https://dash.yunohost.org/integration/mautrix_signal.svg)](https://dash.yunohost.org/appci/app/mautrix_signal) ![Working status](https://ci-apps.yunohost.org/ci/badges/mautrix_signal.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/mautrix_signal.maintain.svg)

[![Install Matrix Signal bridge with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mautrix_signal)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Matrix Signal bridge quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A puppeting bridge between Matrix and Signal packaged as a YunoHost service. Messages, notifications (and sometimes media) are bridged between a Signal user and a Matrix user.
Currently the Matrix user can NOT invite other Matrix user in a bridged Signal room, so only someone with a Signal account can participate to Signal group conversations.

The ["Mautrix-Signal"](https://docs.mau.fi/bridges/python/signal/index.html) bridge consists in a Synapse App Service and relies on postgresql (mysql also possible). Therefore, [Synapse for YunoHost](https://github.com/YunoHost-Apps/synapse_ynh) should be installed beforehand.


**Shipped version:** 0.4.3~ynh1
## Documentation and resources

* Official app website: <https://github.com/mautrix/signal>
* Official user documentation: <https://docs.mau.fi/bridges/python/signal/index.html>
* Upstream app code repository: <https://github.com/mautrix/signal>
* YunoHost Store: <https://apps.yunohost.org/app/mautrix_signal>
* Report a bug: <https://github.com/YunoHost-Apps/mautrix_signal_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/mautrix_signal_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/mautrix_signal_ynh/tree/testing --debug
or
sudo yunohost app upgrade mautrix_signal -u https://github.com/YunoHost-Apps/mautrix_signal_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>