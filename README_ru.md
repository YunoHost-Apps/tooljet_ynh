<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# ToolJet для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/tooljet)](https://ci-apps.yunohost.org/ci/apps/tooljet/)
![Состояние работы](https://apps.yunohost.org/badge/state/tooljet)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/tooljet)

[![Установите ToolJet с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tooljet)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить ToolJet быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

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


**Поставляемая версия:** 2.63.0~ynh1

## Снимки экрана

![Снимок экрана ToolJet](./doc/screenshots/example.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://tooljet.com/>
- Официальная документация пользователя: <https://docs.tooljet.com/docs/intro>
- Репозиторий кода главной ветки приложения: <https://github.com/ToolJet/ToolJet>
- Магазин YunoHost: <https://apps.yunohost.org/app/tooljet>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/tooljet_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing --debug
или
sudo yunohost app upgrade tooljet -u https://github.com/YunoHost-Apps/tooljet_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
