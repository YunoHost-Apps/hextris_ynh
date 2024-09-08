<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Hextris para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/hextris.svg)](https://ci-apps.yunohost.org/ci/apps/hextris/) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/hextris.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/hextris.maintain.svg)

[![Instalar Hextris con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hextris)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Hextris de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

HEXTRIS is a fast paced puzzle game inspired by Tetris.
Blocks start on the edges of the screen, and fall towards the inner blue hexagon.
The objective of the game is to prevent the blocks from stacking outside the area of the grey hexagon.
To do this, you must rotate the hexagon to manage different stacks of blocks on each face.
Aim to connect 3 or more blocks of the same color: when 3 or more blocks of the same color touch each other, they are destroyed, and the blocks above them slide down!
Destroying multiple series of blocks grants combos, whose durations are indicated by a quickly receding outline around the outer, grey hexagon.
You lose once blocks on a face of the hexagon stack outside of the outer hexagon!


**Versión proporcionada:** 2023.06.09~ynh2

**Demo:** <https://hextris.io/>

## Capturas de pantalla

![Captura de pantalla de Hextris](./doc/screenshots/screenshot.jpg)

## Documentación e recursos

- Web oficial da app: <http://hextris.github.io/>
- Repositorio de orixe do código: <https://github.com/Hextris/Hextris>
- Tenda YunoHost: <https://apps.yunohost.org/app/hextris>
- Informar dun problema: <https://github.com/YunoHost-Apps/hextris_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/hextris_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
ou
sudo yunohost app upgrade hextris -u https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
