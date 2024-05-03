<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# ToolJet pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/tooljet.svg)](https://dash.yunohost.org/appci/app/tooljet) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/tooljet.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/tooljet.maintain.svg)

[![Installer ToolJet avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tooljet)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer ToolJet rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

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


**Version incluse :** 2.40.0~ynh1

## Captures d’écran

![Capture d’écran de ToolJet](./doc/screenshots/example.png)

## Documentations et ressources

- Site officiel de l’app : <https://tooljet.com/>
- Documentation officielle utilisateur : <https://docs.tooljet.com/docs/intro>
- Dépôt de code officiel de l’app : <https://github.com/ToolJet/ToolJet>
- YunoHost Store : <https://apps.yunohost.org/app/tooljet>
- Signaler un bug : <https://github.com/YunoHost-Apps/tooljet_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing --debug
ou
sudo yunohost app upgrade tooljet -u https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
