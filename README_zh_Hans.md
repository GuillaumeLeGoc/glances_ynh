<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Glances

[![集成程度](https://apps.yunohost.org/badge/integration/glances)](https://ci-apps.yunohost.org/ci/apps/glances/)
![工作状态](https://apps.yunohost.org/badge/state/glances)
![维护状态](https://apps.yunohost.org/badge/maintained/glances)

[![使用 YunoHost 安装 Glances](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=glances)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Glances。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Glances is a cross-platform monitoring tool that aims to present maximum information in minimal space through either a curses-based or Web-based interface. It can dynamically adapt the displayed information depending on the terminal size.


**分发版本：** 4.3.0.8~ynh1

## 截图

![Glances 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://nicolargo.github.io/glances/?ref=selfh.st>
- 官方管理文档： <https://glances.readthedocs.io/en/latest/index.html>
- 上游应用代码库： <https://github.com/nicolargo/glances>
- YunoHost 商店： <https://apps.yunohost.org/app/glances>
- 报告 bug： <https://github.com/YunoHost-Apps/glances_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/glances_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/glances_ynh/tree/testing --debug
或
sudo yunohost app upgrade glances -u https://github.com/YunoHost-Apps/glances_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
