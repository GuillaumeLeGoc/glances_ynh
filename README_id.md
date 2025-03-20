<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Glances untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/glances)](https://ci-apps.yunohost.org/ci/apps/glances/)
![Status kerja](https://apps.yunohost.org/badge/state/glances)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/glances)

[![Pasang Glances dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=glances)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Glances secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Glances is a cross-platform monitoring tool that aims to present maximum information in minimal space through either a curses-based or Web-based interface. It can dynamically adapt the displayed information depending on the terminal size.


**Versi terkirim:** 4.3.0.8~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Glances](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://nicolargo.github.io/glances/?ref=selfh.st>
- Dokumentasi admin resmi: <https://glances.readthedocs.io/en/latest/index.html>
- Depot kode aplikasi hulu: <https://github.com/nicolargo/glances>
- Gudang YunoHost: <https://apps.yunohost.org/app/glances>
- Laporkan bug: <https://github.com/YunoHost-Apps/glances_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/glances_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/glances_ynh/tree/testing --debug
atau
sudo yunohost app upgrade glances -u https://github.com/YunoHost-Apps/glances_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
