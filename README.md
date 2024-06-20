<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Hextris for YunoHost

[![Integration level](https://dash.yunohost.org/integration/hextris.svg)](https://dash.yunohost.org/appci/app/hextris) ![Working status](https://ci-apps.yunohost.org/ci/badges/hextris.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/hextris.maintain.svg)

[![Install Hextris with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hextris)

*[Read this README is other languages.](./ALL_README.md)*

> *This package allows you to install Hextris quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

HEXTRIS is a fast paced puzzle game inspired by Tetris.
Blocks start on the edges of the screen, and fall towards the inner blue hexagon.
The objective of the game is to prevent the blocks from stacking outside the area of the grey hexagon.
To do this, you must rotate the hexagon to manage different stacks of blocks on each face.
Aim to connect 3 or more blocks of the same color: when 3 or more blocks of the same color touch each other, they are destroyed, and the blocks above them slide down!
Destroying multiple series of blocks grants combos, whose durations are indicated by a quickly receding outline around the outer, grey hexagon.
You lose once blocks on a face of the hexagon stack outside of the outer hexagon!


**Shipped version:** 2023.06.09~ynh1

**Demo:** <https://hextris.io/>

## Screenshots

![Screenshot of Hextris](./doc/screenshots/screenshot.jpg)

## Documentation and resources

<<<<<<< HEAD
* Official app website: <http://hextris.github.io/>
* Upstream app code repository: <https://github.com/Hextris/Hextris>
* YunoHost Store: <https://apps.yunohost.org/app/hextris>
* Report a bug: <https://github.com/YunoHost-Apps/hextris_ynh/issues>
=======
- Official app website: <http://hextris.github.io/>
- Upstream app code repository: <https://github.com/Hextris/Hextris>
- YunoHost Store: <https://apps.yunohost.org/app/hextris>
- Report a bug: <https://github.com/YunoHost-Apps/hextris_ynh/issues>
>>>>>>> master

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/hextris_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
or
sudo yunohost app upgrade hextris -u https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
