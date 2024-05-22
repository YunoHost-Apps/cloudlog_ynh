<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# CloudLog YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/cloudlog.svg)](https://dash.yunohost.org/appci/app/cloudlog) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/cloudlog.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/cloudlog.maintain.svg)

[![Instalatu CloudLog YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cloudlog)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek CloudLog YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Cloudlog is an open-source PHP & MySQL based amateur radio logging application, allowing you to log contacts via a web browser on any device and platform.

This is an ideal general-purpose logging application, supporting HF to Microwave, it can even interface with your radio via CAT, sync logs from WSJT-X & if you are a satellite operator integrates with SatPC32.

**Paketatutako bertsioa:** 2.6.13~ynh1

## Pantaila-argazkiak

![CloudLog(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.cloudlog.co.uk>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/magicbug/Cloudlog>
- YunoHost Denda: <https://apps.yunohost.org/app/cloudlog>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/cloudlog_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing --debug
edo
sudo yunohost app upgrade cloudlog -u https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
