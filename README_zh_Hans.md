<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Hextris

[![集成程度](https://dash.yunohost.org/integration/hextris.svg)](https://ci-apps.yunohost.org/ci/apps/hextris/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/hextris.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/hextris.maintain.svg)

[![使用 YunoHost 安装 Hextris](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hextris)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Hextris。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

HEXTRIS is a fast paced puzzle game inspired by Tetris.
Blocks start on the edges of the screen, and fall towards the inner blue hexagon.
The objective of the game is to prevent the blocks from stacking outside the area of the grey hexagon.
To do this, you must rotate the hexagon to manage different stacks of blocks on each face.
Aim to connect 3 or more blocks of the same color: when 3 or more blocks of the same color touch each other, they are destroyed, and the blocks above them slide down!
Destroying multiple series of blocks grants combos, whose durations are indicated by a quickly receding outline around the outer, grey hexagon.
You lose once blocks on a face of the hexagon stack outside of the outer hexagon!


**分发版本：** 2023.06.09~ynh1

**演示：** <https://hextris.io/>

## 截图

![Hextris 的截图](./doc/screenshots/screenshot.jpg)

## 文档与资源

- 官方应用网站： <http://hextris.github.io/>
- 上游应用代码库： <https://github.com/Hextris/Hextris>
- YunoHost 商店： <https://apps.yunohost.org/app/hextris>
- 报告 bug： <https://github.com/YunoHost-Apps/hextris_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/hextris_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
或
sudo yunohost app upgrade hextris -u https://github.com/YunoHost-Apps/hextris_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
