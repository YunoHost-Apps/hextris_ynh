<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Hextris YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/hextris.svg)](https://ci-apps.yunohost.org/ci/apps/hextris/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/hextris.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/hextris.maintain.svg)

[![Instalatu Hextris YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hextris)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Hextris YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

HEXTRIS is a fast paced puzzle game inspired by Tetris.
Blocks start on the edges of the screen, and fall towards the inner blue hexagon.
The objective of the game is to prevent the blocks from stacking outside the area of the grey hexagon.
To do this, you must rotate the hexagon to manage different stacks of blocks on each face.
Aim to connect 3 or more blocks of the same color: when 3 or more blocks of the same color touch each other, they are destroyed, and the blocks above them slide down!
Destroying multiple series of blocks grants combos, whose durations are indicated by a quickly receding outline around the outer, grey hexagon.
You lose once blocks on a face of the hexagon stack outside of the outer hexagon!


**Paketatutako bertsioa:** 2023.06.09~ynh2

**Demoa:** <https://hextris.io/>

## Pantaila-argazkiak

![Hextris(r)en pantaila-argazkia](./doc/screenshots/screenshot.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <http://hextris.github.io/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/Hextris/Hextris>
- YunoHost Denda: <https://apps.yunohost.org/app/hextris>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/hextris_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/hextris_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
edo
sudo yunohost app upgrade hextris -u https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
