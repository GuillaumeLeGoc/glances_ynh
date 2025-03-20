<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Glances YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/glances)](https://ci-apps.yunohost.org/ci/apps/glances/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/glances)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/glances)

[![Instalatu Glances YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=glances)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Glances YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Glances is a cross-platform monitoring tool that aims to present maximum information in minimal space through either a curses-based or Web-based interface. It can dynamically adapt the displayed information depending on the terminal size.


**Paketatutako bertsioa:** 4.3.0.8~ynh1

## Pantaila-argazkiak

![Glances(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://nicolargo.github.io/glances/?ref=selfh.st>
- Administratzaileen dokumentazio ofiziala: <https://glances.readthedocs.io/en/latest/index.html>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/nicolargo/glances>
- YunoHost Denda: <https://apps.yunohost.org/app/glances>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/glances_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/glances_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/glances_ynh/tree/testing --debug
edo
sudo yunohost app upgrade glances -u https://github.com/YunoHost-Apps/glances_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
