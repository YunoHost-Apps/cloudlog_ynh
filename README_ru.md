<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# CloudLog для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/cloudlog.svg)](https://ci-apps.yunohost.org/ci/apps/cloudlog/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/cloudlog.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/cloudlog.maintain.svg)

[![Установите CloudLog с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cloudlog)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить CloudLog быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Cloudlog is an open-source PHP & MySQL based amateur radio logging application, allowing you to log contacts via a web browser on any device and platform.

This is an ideal general-purpose logging application, supporting HF to Microwave, it can even interface with your radio via CAT, sync logs from WSJT-X & if you are a satellite operator integrates with SatPC32.

**Поставляемая версия:** 2.6.15~ynh2

## Снимки экрана

![Снимок экрана CloudLog](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://www.cloudlog.co.uk>
- Репозиторий кода главной ветки приложения: <https://github.com/magicbug/Cloudlog>
- Магазин YunoHost: <https://apps.yunohost.org/app/cloudlog>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/cloudlog_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing --debug
или
sudo yunohost app upgrade cloudlog -u https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
