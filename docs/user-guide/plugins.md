---
title: 插件
description: 插件管理相关功能说明
---

插件时用于扩展 Halo 功能的软件包。插件独立于 Halo 核心应用，可以单独安装、升级、卸载。

:::info
当前 Halo 支持的插件可在[Awesome Halo](https://github.com/halo-sigs/awesome-halo)仓库查看。
:::

本文档仅对插件的基本管理功能进行说明，关于插件的详细使用说明请参考对应插件的文档。

## 安装插件

点击插件页面右上角的 `安装` 按钮，在弹出的文件上传对话框中上传插件文件即可完成插件安装。

![安装插件](/img/user-guide/plugins/plugin-install.png)

插件安装成功后，便会出现在已安装主题列表中。你可以点击某个插件进入到插件详情页面。

## 插件设置

点击插件列表中的某个插件进入插件详情页面。与主题设置类似，插件详情页面默认显示出了当前插件的详细信息，在详细信息标签页后方的标签页，即为插件提供的相关设置。不同的插件提供的设置项各不相同，设置项的详细说明请参考对应插件的文档。

![插件设置](/img/user-guide/plugins/plugin-setting.png)

以 Unsplash 插件为例，该提供仅在基本设置组中提供了 `Access Key` 一项配置，用于调用 Unsplash 接口。

:::info
你可以点击插件列表指定插件所在行后方的 `···` 更多操作按钮，选择其中的 `重置` 选项将插件提供的设置项恢复为默认值。
:::

## 启用/禁用插件

点击插件列表或插件详情页中的启用/禁用开关，即可切换插件的启用禁用状态。

![插件启用/禁用](/img/user-guide/plugins/plugin-switch.png)

## 升级插件

点击插件列表指定插件所在行后方的 `···` 更多操作按钮，选择其中的 `升级` 选项即可上传新的插件文件对当前插件进行升级。

## 卸载插件

点击插件列表指定插件所在行后方的 `···` 更多操作按钮，选择其中的 `卸载` 选项即可对当前插件进行卸载。
![卸载插件](/img/user-guide/plugins/plugin-uninstall.png)

:::info
目前提供了 `卸载` 及 `卸载并删除配置` 两种卸载方式。
仅卸载插件时插件的配置信息会进行保留，当重新安装插件后还可以使用之前已保存的配置。
:::
