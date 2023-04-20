<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# ToolJet for YunoHost

[![Integration level](https://dash.yunohost.org/integration/tooljet.svg)](https://dash.yunohost.org/appci/app/tooljet) ![Working status](https://ci-apps.yunohost.org/ci/badges/tooljet.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/tooljet.maintain.svg)

[![Install ToolJet with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tooljet)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install ToolJet quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

ToolJet is an open-source low-code framework to build and deploy internal tools quickly without much effort from the engineering teams. You can connect to your data sources, such as databases (like PostgreSQL, MongoDB, Elasticsearch, etc), API endpoints (ToolJet supports importing OpenAPI spec & OAuth2 authorization), and external services (like Stripe, Slack, Google Sheets, Airtable) and use our pre-built UI widgets to build internal tools.

### Features

- *Visual app builder:* 35+ built-in responsive widgets such as Tables, Charts, Lists, Forms, Progressbars, and more.
- *20+ data sources:* connect to databases, cloud storages and APIs.
- *Desktop & mobile*: ;layout widths can be customised to support different screens. 
- *Collaborate:* add comments anywhere on the canvas and tag your team members.
- *Extend with plugins:*: use our [commandline tool](https://www.npmjs.com/package/tooljet) to easily boostrap new connectors.
- *Version control:* every application have different versions with proper release cycle.
- *Run JS code:* ability custom JavaScript snippets
- *Granular access control* on organization-level and app-level.
- *low-code:* write JS code almost anywhere in the builder. For example, the color property of text can be set to `status === 'success' ? 'green' : 'red'`
- *no-code query editors* for all supported data sources.
- *Join and transform data:* transform query results using just JavaScript code. 
- *Secure:* All the credentials are securely encrypted using `aes-256-gcm`.
- *Doesn't store data:* ToolJet acts only as a proxy and doesn't store any data.


**Shipped version:** 2.4.8~ynh1

## Screenshots

![Screenshot of ToolJet](./doc/screenshots/example.png)

## Disclaimers / important information

### After installation

TODO

### Limitations

* Require YunoHost 11.
* This app requires a full dedicated domain (or subdomain), with a signed certificate.
* Single Sign-On and LDAP integration does *not* work.

## Documentation and resources

* Official app website: <https://tooljet.com/>
* Official user documentation: <https://docs.tooljet.com/docs/intro>
* Upstream app code repository: <https://github.com/ToolJet/ToolJet>
* YunoHost documentation for this app: <https://yunohost.org/app_tooljet>
* Report a bug: <https://github.com/YunoHost-Apps/tooljet_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing --debug
or
sudo yunohost app upgrade tooljet -u https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
