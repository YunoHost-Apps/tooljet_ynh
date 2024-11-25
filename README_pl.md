<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# ToolJet dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/tooljet)](https://ci-apps.yunohost.org/ci/apps/tooljet/)
![Status działania](https://apps.yunohost.org/badge/state/tooljet)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/tooljet)

[![Zainstaluj ToolJet z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tooljet)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację ToolJet na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

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


**Dostarczona wersja:** 2.63.0~ynh1

## Zrzuty ekranu

![Zrzut ekranu z ToolJet](./doc/screenshots/example.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://tooljet.com/>
- Oficjalna dokumentacja: <https://docs.tooljet.com/docs/intro>
- Repozytorium z kodem źródłowym: <https://github.com/ToolJet/ToolJet>
- Sklep YunoHost: <https://apps.yunohost.org/app/tooljet>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/tooljet_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing --debug
lub
sudo yunohost app upgrade tooljet -u https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
