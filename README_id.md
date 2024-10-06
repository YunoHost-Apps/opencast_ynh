<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Opencast untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/opencast.svg)](https://ci-apps.yunohost.org/ci/apps/opencast/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/opencast.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/opencast.maintain.svg)

[![Pasang Opencast dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opencast)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Opencast secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Opencast is a free, open-source platform to support the management of educational audio and video content. Institutions can use Opencast to produce lecture recordings, manage existing video, serve designated distribution channels, and provide user interfaces to engage students with educational videos.


**Versi terkirim:** 16.5~ynh1

**Demo:** <https://stable.opencast.org/admin-ui/index.html>

## Tangkapan Layar

![Tangkapan Layar pada Opencast](./doc/screenshots/screeshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://opencast.org/>
- Dokumentasi admin resmi: <https://docs.opencast.org/develop/admin/#>
- Depot kode aplikasi hulu: <https://github.com/opencast/opencast>
- Gudang YunoHost: <https://apps.yunohost.org/app/opencast>
- Laporkan bug: <https://github.com/YunoHost-Apps/opencast_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/opencast_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opencast_ynh/tree/testing --debug
atau
sudo yunohost app upgrade opencast -u https://github.com/YunoHost-Apps/opencast_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
