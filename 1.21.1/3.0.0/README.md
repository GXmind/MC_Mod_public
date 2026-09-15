# 墨韵 InkBrush 3.0.0

适用环境：

- Minecraft Java Edition 1.21.1
- NeoForge 21.1.250 或同系列兼容更新版
- Java 21

文件：`inkbrush-3.0.0+mc1.21.1-neoforge.jar`

## 版本说明

- 将 1.21.11 版本已有的毛笔、墨水、双技能组、太极阵、乾坤移位、墨锁囚灵、死生判笔、封魔绘图、画布、字帖、笔筒、笔架及洗笔染池机制移植到 Minecraft 1.21.1。
- 使用独立的 `neoforge-1.21.1` 项目适配层，并继续复用公共逻辑组件。
- 适配 NeoForge 1.21.1 的注册、网络、数据组件、物品模型与即时渲染 API。
- 为 Photon 2 编辑测试预留可选客户端依赖；未安装 Photon 2 时 InkBrush 仍可独立运行。

## 安装

1. 安装 Minecraft 1.21.1 与 NeoForge 21.1.250。
2. 将本目录中的 JAR 放入该实例的 `mods` 文件夹。
3. 删除该实例中其他 Minecraft 版本或旧版 InkBrush JAR。
4. 如需使用 Photon 2 编辑器，额外安装与 1.21.1 匹配的 Photon 2 和 LDLib2。

本公开包仅包含编译产物与说明，不包含源代码。
