# 墨韵 InkBrush

Minecraft Java Edition 毛笔武器模组的公开发布仓库。本仓库仅提供编译完成的 JAR 与版本说明，不包含源代码。

## 版本下载

| Minecraft | 加载器 | 模组版本 | 下载与说明 |
| --- | --- | --- | --- |
| 1.20.1 | Fabric | 1.0.0 | [进入 1.20.1 目录](./1.20.1/) |
| 1.21.11 | Forge 61.2.1 | 2.0.1.0-vfx-env（VFX + 环境联动测试版） | [进入 1.21.11 目录](./1.21.11/) |

每个 Minecraft 版本均使用独立目录，其中只包含该版本的 JAR 和独立 `README.md`。请勿把不同游戏版本或不同加载器的 JAR 混用。

## 仓库结构

```text
1.20.1/
├─ README.md
└─ inkbrush-1.0.0+mc1.20.1.jar

1.21.11/
├─ README.md
├─ 1.2.0/
│  ├─ README.md
│  └─ inkbrush-1.2.0+mc1.21.11-forge.jar
├─ 1.4.0/
│  ├─ README.md
│  └─ inkbrush-1.4.0+mc1.21.11-forge.jar
├─ 1.4.1/
│  ├─ README.md
│  └─ inkbrush-1.4.1+mc1.21.11-forge.jar
├─ 1.5.0/
│  ├─ README.md
│  └─ inkbrush-1.5.0+mc1.21.11-forge.jar
├─ 1.5.3-disable_vfs/
│  ├─ README.md
│  └─ inkbrush-1.5.3-disable_vfs+mc1.21.11-forge.jar
├─ 1.5.4-release/
│  ├─ README.md
│  └─ inkbrush-1.5.4-release+mc1.21.11-forge.jar
├─ 1.6.0-vfs-release/
│  ├─ README.md
│  └─ inkbrush-1.6.0+mc1.21.11-forge.jar
├─ 2.0.0/
│  ├─ README.md
│  └─ inkbrush-2.0.0+mc1.21.11-forge.jar
├─ 2.0.1-vfx/
│  ├─ README.md
│  └─ inkbrush-2.0.1-vfx+mc1.21.11-forge.jar
└─ 2.0.1.0-vfx-env/
   ├─ README.md
   └─ 1.21.11_vfx_env_2.0.1.0.jar
```

## 通用安装方法

1. 根据 Minecraft 版本安装目录中标明的加载器及依赖。
2. 下载对应版本目录内的 JAR。
3. 将 JAR 放入该游戏实例的 `mods` 文件夹。
4. 删除同一模组的旧版或其他 Minecraft 版本 JAR，然后启动游戏。

## 闭源说明

本仓库仅用于分发可运行的模组文件及说明文档。源代码未在此仓库公开。
