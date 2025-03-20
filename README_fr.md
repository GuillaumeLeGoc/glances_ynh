<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Glances pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/glances)](https://ci-apps.yunohost.org/ci/apps/glances/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/glances)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/glances)

[![Installer Glances avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=glances)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Glances rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Glances est un outil de surveillance multiplateforme qui vise à présenter un maximum d'informations dans un minimum d'espace par le biais d'une interface basée sur curses ou sur le Web. Il peut adapter dynamiquement les informations affichées en fonction de la taille du terminal.


**Version incluse :** 4.3.0.8~ynh1

## Captures d’écran

![Capture d’écran de Glances](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://nicolargo.github.io/glances/?ref=selfh.st>
- Documentation officielle de l’admin : <https://glances.readthedocs.io/en/latest/index.html>
- Dépôt de code officiel de l’app : <https://github.com/nicolargo/glances>
- YunoHost Store : <https://apps.yunohost.org/app/glances>
- Signaler un bug : <https://github.com/YunoHost-Apps/glances_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/glances_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/glances_ynh/tree/testing --debug
ou
sudo yunohost app upgrade glances -u https://github.com/YunoHost-Apps/glances_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
