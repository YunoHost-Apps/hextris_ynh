<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Hextris per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/hextris.svg)](https://dash.yunohost.org/appci/app/hextris) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/hextris.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/hextris.maintain.svg)

[![Installa Hextris con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hextris)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Hextris su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

HEXTRIS is a fast paced puzzle game inspired by Tetris.
Blocks start on the edges of the screen, and fall towards the inner blue hexagon.
The objective of the game is to prevent the blocks from stacking outside the area of the grey hexagon.
To do this, you must rotate the hexagon to manage different stacks of blocks on each face.
Aim to connect 3 or more blocks of the same color: when 3 or more blocks of the same color touch each other, they are destroyed, and the blocks above them slide down!
Destroying multiple series of blocks grants combos, whose durations are indicated by a quickly receding outline around the outer, grey hexagon.
You lose once blocks on a face of the hexagon stack outside of the outer hexagon!


**Versione pubblicata:** 2023.06.09~ynh1

**Prova:** <https://hextris.io/>

## Screenshot

![Screenshot di Hextris](./doc/screenshots/screenshot.jpg)

## Documentazione e risorse

- Sito web ufficiale dell’app: <http://hextris.github.io/>
- Repository upstream del codice dell’app: <https://github.com/Hextris/Hextris>
- Store di YunoHost: <https://apps.yunohost.org/app/hextris>
- Segnala un problema: <https://github.com/YunoHost-Apps/hextris_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/hextris_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
o
sudo yunohost app upgrade hextris -u https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
