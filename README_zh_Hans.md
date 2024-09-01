<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 CloudLog

[![集成程度](https://dash.yunohost.org/integration/cloudlog.svg)](https://ci-apps.yunohost.org/ci/apps/cloudlog/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/cloudlog.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/cloudlog.maintain.svg)

[![使用 YunoHost 安装 CloudLog](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cloudlog)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 CloudLog。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Cloudlog is an open-source PHP & MySQL based amateur radio logging application, allowing you to log contacts via a web browser on any device and platform.

This is an ideal general-purpose logging application, supporting HF to Microwave, it can even interface with your radio via CAT, sync logs from WSJT-X & if you are a satellite operator integrates with SatPC32.

**分发版本：** 2.6.15~ynh2

## 截图

![CloudLog 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://www.cloudlog.co.uk>
- 上游应用代码库： <https://github.com/magicbug/Cloudlog>
- YunoHost 商店： <https://apps.yunohost.org/app/cloudlog>
- 报告 bug： <https://github.com/YunoHost-Apps/cloudlog_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing --debug
或
sudo yunohost app upgrade cloudlog -u https://github.com/YunoHost-Apps/cloudlog_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
