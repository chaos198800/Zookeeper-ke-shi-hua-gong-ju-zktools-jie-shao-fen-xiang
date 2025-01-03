# Zookeeper 可视化工具 zktools 介绍

## 概述
zktools 是一款由 JavaFX 开发的 Zookeeper 可视化工具，旨在帮助用户更方便地管理和监控 Zookeeper 集群。该工具提供了直观的图形界面，使用户能够轻松查看、创建、修改和删除 Zookeeper 节点。

## 功能特点
1. **节点管理**：
   - 查看 Zookeeper 节点树结构。
   - 创建、修改和删除节点。
   - 支持 URL 编码和解码节点名，提高可读性。

2. **实时监控**：
   - 实时展示节点变化，包括节点增加或删除。
   - 显示节点的详细信息，如节点名、节点值、节点属性等。

3. **搜索功能**：
   - 支持关键字搜索，快速定位关心的节点。
   - 命中节点关键字部分会变红，方便识别。

4. **日志查看**：
   - 显示监控日志，节点发生变化时会在该处打印日志。

## 使用方法
1. **前置条件**：
   - 安装 JDK 1.8 及以上版本，并配置好环境变量。

2. **软件目录**：
   - `zktools.exe`：双击启动软件，使用 `javaw` 启动。
   - `bin` 目录：存放软件的启动脚本，包括 `java-start.cmd` 和 `javaw-start.cmd`。
   - `lib` 目录：存放软件使用到的所有 JAR 文件。

3. **启动方式**：
   - 双击 `zktools.exe` 启动。
   - 双击 `bin/java-start.cmd` 启动，软件启动后会有一个 CMD 窗口，可查看日志信息。
   - 双击 `bin/javaw-start.cmd` 启动，使用 `javaw` 启动软件，CMD 窗口会自动消失。

4. **软件界面**：
   - 输入 Zookeeper 地址，如 `127.0.0.1:2181`。
   - 监控根节点，可输入关心的节点路径，如 `/dubbo`。
   - 点击“开始链接”按钮，链接 Zookeeper 集群。
   - 点击“断开链接”按钮，断开链接并释放资源。
   - 输入关键字搜索节点，点击“开始查询”按钮，命中节点关键字部分会变红。

## 注意事项
- 360 软件可能会报告 `zktools.exe` 为病毒，但可以点击 `bin` 目录下的文件启动。
- 节点较多时，使用搜索功能能够快速找到关心的节点。

## 反馈与支持
- 点击菜单栏中的“反馈”，选择“需求”或“BUG”，弹出相应的对话框。
- 也可以将您的需求发送至 `rongbaojian110@163.com`。

## 结语
zktools 是一款功能强大且易于使用的 Zookeeper 可视化工具，能够极大地提升 Zookeeper 集群的管理效率。希望您在使用过程中能够获得良好的体验。

## 下载链接

[Zookeeper可视化工具zktools介绍分享](https://pan.quark.cn/s/885122a2d224)