<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Hextris voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/hextris)](https://ci-apps.yunohost.org/ci/apps/hextris/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/hextris)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/hextris)

[![Hextris met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hextris)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Hextris snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

HEXTRIS is a fast paced puzzle game inspired by Tetris.
Blocks start on the edges of the screen, and fall towards the inner blue hexagon.
The objective of the game is to prevent the blocks from stacking outside the area of the grey hexagon.
To do this, you must rotate the hexagon to manage different stacks of blocks on each face.
Aim to connect 3 or more blocks of the same color: when 3 or more blocks of the same color touch each other, they are destroyed, and the blocks above them slide down!
Destroying multiple series of blocks grants combos, whose durations are indicated by a quickly receding outline around the outer, grey hexagon.
You lose once blocks on a face of the hexagon stack outside of the outer hexagon!


**Geleverde versie:** 2023.06.09~ynh2

**Demo:** <https://hextris.io/>

## Schermafdrukken

![Schermafdrukken van Hextris](./doc/screenshots/screenshot.jpg)

## Documentatie en bronnen

- Officiele website van de app: <http://hextris.github.io/>
- Upstream app codedepot: <https://github.com/Hextris/Hextris>
- YunoHost-store: <https://apps.yunohost.org/app/hextris>
- Meld een bug: <https://github.com/YunoHost-Apps/hextris_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/hextris_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
of
sudo yunohost app upgrade hextris -u https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
