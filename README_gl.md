<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# ToolJet para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/tooljet.svg)](https://dash.yunohost.org/appci/app/tooljet) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/tooljet.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/tooljet.maintain.svg)

[![Instalar ToolJet con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tooljet)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar ToolJet de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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


**Versión proporcionada:** 2.61.3~ynh1

## Capturas de pantalla

![Captura de pantalla de ToolJet](./doc/screenshots/example.png)

## Documentación e recursos

- Web oficial da app: <https://tooljet.com/>
- Documentación oficial para usuarias: <https://docs.tooljet.com/docs/intro>
- Repositorio de orixe do código: <https://github.com/ToolJet/ToolJet>
- Tenda YunoHost: <https://apps.yunohost.org/app/tooljet>
- Informar dun problema: <https://github.com/YunoHost-Apps/tooljet_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing --debug
ou
sudo yunohost app upgrade tooljet -u https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
