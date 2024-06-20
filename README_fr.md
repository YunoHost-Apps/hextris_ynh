<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Hextris pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/hextris.svg)](https://dash.yunohost.org/appci/app/hextris) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/hextris.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/hextris.maintain.svg)

[![Installer Hextris avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hextris)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Hextris rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

HEXTRIS est un jeu de puzzle au rythme rapide inspiré de Tetris.
Les blocs commencent sur les bords de l'écran, et tombent vers l'hexagone bleu intérieur.
Le but du jeu est d'empêcher les blocs de s'empiler en dehors de la zone de l'hexagone gris.
Pour ce faire, vous devez faire tourner l'hexagone pour gérer différentes piles de blocs sur chaque face.
Visez à relier 3 blocs ou plus de la même couleur : lorsque 3 blocs ou plus de la même couleur se touchent, ils sont détruits, et les blocs au-dessus d'eux glissent vers le bas !
Détruire plusieurs séries de blocs permet d'obtenir des combos, dont la durée est indiquée par un contour qui s'estompe rapidement autour de l'hexagone extérieur gris.
Vous perdez une fois les blocs sur une face de la pile hexagonale en dehors de l'hexagone extérieur !


<<<<<<< HEAD
**Version incluse :** 2023.06.09~ynh1
=======
**Version incluse :** 2023.06.09~ynh1
>>>>>>> master

**Démo :** <https://hextris.io/>

## Captures d’écran

![Capture d’écran de Hextris](./doc/screenshots/screenshot.jpg)

## Documentations et ressources

<<<<<<< HEAD
* Site officiel de l’app : <http://hextris.github.io/>
* Dépôt de code officiel de l’app : <https://github.com/Hextris/Hextris>
* YunoHost Store: <https://apps.yunohost.org/app/hextris>
* Signaler un bug : <https://github.com/YunoHost-Apps/hextris_ynh/issues>
=======
- Site officiel de l’app : <http://hextris.github.io/>
- Dépôt de code officiel de l’app : <https://github.com/Hextris/Hextris>
- YunoHost Store : <https://apps.yunohost.org/app/hextris>
- Signaler un bug : <https://github.com/YunoHost-Apps/hextris_ynh/issues>
>>>>>>> master

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/hextris_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
ou
sudo yunohost app upgrade hextris -u https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
