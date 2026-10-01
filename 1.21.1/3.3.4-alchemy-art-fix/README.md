# 墨韵 InkAura 3.3.4-alchemy-art-fix

适用环境：Minecraft Java Edition `1.21.1`、NeoForge `21.1.250`、Java 21。

模组文件：`inkaura-3.3.4-alchemy-art-fix+mc1.21.1-neoforge.jar`

## 本次更新

- 六种炼丹炉采用占地 2×2 的炉型模型，新增对应的独立材质与物品外观。
- 丹药根据品质、属性和特殊类别使用不同的三维模型；丹渣与丹方书也使用独立模型。
- 修复炉腹太极徽分块错位：放置后的炉子只绘制一枚完整的太极徽。
- 修复丹药着色缺少不透明度导致模型透明的问题，并调整炼丹界面外观。

内部模组 ID 仍为 `inkbrush`，用于兼容旧存档与资源。

## 安装

将 JAR 放入 1.21.1 NeoForge 实例的 `mods` 目录，并移除或禁用旧版 InkAura/InkBrush JAR；不要同时加载多个版本。Photon 2、LDLib2 与 KilaGraph 为可选特效编辑环境，不是本模组的强制依赖。

## 校验

SHA-256：`A18E024A09172A4BB3F026EED847C35F1F288C7A8B8A5CB3F982070EC3518C00`

已通过 NeoForge 完整构建、资源与架构校验；此次修复尚未完成游戏内实测。本公开目录只包含 JAR 和说明文档，不包含源代码。
