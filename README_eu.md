<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Opencast YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/opencast)](https://ci-apps.yunohost.org/ci/apps/opencast/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/opencast)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/opencast)

[![Instalatu Opencast YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opencast)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Opencast YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Opencast is a free, open-source platform to support the management of educational audio and video content. Institutions can use Opencast to produce lecture recordings, manage existing video, serve designated distribution channels, and provide user interfaces to engage students with educational videos.


**Paketatutako bertsioa:** 15.0~ynh1

**Demoa:** <https://stable.opencast.org/admin-ui/index.html>

## Pantaila-argazkiak

![Opencast(r)en pantaila-argazkia](./doc/screenshots/screeshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://opencast.org/>
- Administratzaileen dokumentazio ofiziala: <https://docs.opencast.org/develop/admin/#>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/opencast/opencast>
- YunoHost Denda: <https://apps.yunohost.org/app/opencast>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/opencast_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/opencast_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opencast_ynh/tree/testing --debug
edo
sudo yunohost app upgrade opencast -u https://github.com/YunoHost-Apps/opencast_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
