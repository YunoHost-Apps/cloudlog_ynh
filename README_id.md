<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# CloudLog untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/cloudlog)](https://ci-apps.yunohost.org/ci/apps/cloudlog/)
![Status kerja](https://apps.yunohost.org/badge/state/cloudlog)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/cloudlog)

[![Pasang CloudLog dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cloudlog)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang CloudLog secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Cloudlog is an open-source PHP & MySQL based amateur radio logging application, allowing you to log contacts via a web browser on any device and platform.

This is an ideal general-purpose logging application, supporting HF to Microwave, it can even interface with your radio via CAT, sync logs from WSJT-X & if you are a satellite operator integrates with SatPC32.

**Versi terkirim:** 2.6.17~ynh1

## Tangkapan Layar

![Tangkapan Layar pada CloudLog](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.cloudlog.co.uk>
- Depot kode aplikasi hulu: <https://github.com/magicbug/Cloudlog>
- Gudang YunoHost: <https://apps.yunohost.org/app/cloudlog>
- Laporkan bug: <https://github.com/YunoHost-Apps/cloudlog_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing --debug
atau
sudo yunohost app upgrade cloudlog -u https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
