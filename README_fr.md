<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# CloudLog pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/cloudlog.svg)](https://ci-apps.yunohost.org/ci/apps/cloudlog/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/cloudlog.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/cloudlog.maintain.svg)

[![Installer CloudLog avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cloudlog)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer CloudLog rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Cloudlog est une application de journalisation radio amateur open-source basée sur PHP et MySQL, vous permettant de consigner des contacts via un navigateur Web sur n'importe quel appareil et plate-forme.

Il s'agit d'une application de journalisation polyvalente idéale, prenant en charge HF vers micro-ondes, elle peut même s'interfacer avec votre radio via CAT, synchroniser les journaux de WSJT-X et si vous êtes un opérateur satellite, s'intègre à SatPC32.

**Version incluse :** 2.6.16~ynh1

## Captures d’écran

![Capture d’écran de CloudLog](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.cloudlog.co.uk>
- Dépôt de code officiel de l’app : <https://github.com/magicbug/Cloudlog>
- YunoHost Store : <https://apps.yunohost.org/app/cloudlog>
- Signaler un bug : <https://github.com/YunoHost-Apps/cloudlog_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing --debug
ou
sudo yunohost app upgrade cloudlog -u https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
