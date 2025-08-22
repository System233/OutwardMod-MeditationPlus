

# MeditationPlus

允许玩家坐下以恢复状态，支持本地分屏和控制器。

[English](./README.md), [中文](./README.CN.md)

## 用法

长按**收起武器**键坐下，无需任何额外键位，不影响原有功能。
* 对于键盘，默认为**Z**。
* 对于控制器，默认为**方向键下**。
* 可以在设置中调整键位。


## 构建

1. 符号链接游戏的Managed目录到本目录
2. 安装dotnet sdk
3. 执行以下命令
```sh
dotnet nuget add source https://nuget.bepinex.dev/v3/index.json -n BepInEx
dotnet build -c Release
```

输出位于 `bin\Release\net472\MeditationPlus.dll`

## 致谢
感谢 SavanticIO 的 [Meditation](https://github.com/SavanticIO/OutwardMods/tree/master/Meditation) Mod，本mod在此基础上改进而来。


## 许可证

[MIT LICENSE](./LICENSE)