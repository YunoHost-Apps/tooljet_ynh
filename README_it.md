<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# ToolJet per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/tooljet.svg)](https://dash.yunohost.org/appci/app/tooljet) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/tooljet.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/tooljet.maintain.svg)

[![Installa ToolJet con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tooljet)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare ToolJet su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

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


**Versione pubblicata:** 2.34.0~ynh1

## Screenshot

![Screenshot di ToolJet](./doc/screenshots/example.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://tooljet.com/>
- Documentazione ufficiale per gli utenti: <https://docs.tooljet.com/docs/intro>
- Repository upstream del codice dell’app: <https://github.com/ToolJet/ToolJet>
- Store di YunoHost: <https://apps.yunohost.org/app/tooljet>
- Segnala un problema: <https://github.com/YunoHost-Apps/tooljet_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing --debug
o
sudo yunohost app upgrade tooljet -u https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
