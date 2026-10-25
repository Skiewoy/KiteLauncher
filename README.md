# MyLauncher

轻量Minecraft启动器v1.0.0版本，目前仅支持windows系统

## 特性

- **单文件** —— 下载后可直接双击打开
- **模组 / 整合包** —— 从 Modrinth 搜索下载，整合包自动解成独立版本
- **账号** —— 微软正版登录、LittleSkin 等外置登录、离线模式
- **自动优化** —— 按硬件和模组数量推荐内存与 JVM 参数，可一键回退，目前可能遇到bug请及时反馈
- **自定义外观** —— 四套视觉风格、可导入背景图、拖拽式布局，目前未做完
- **崩溃诊断** —— 启动失败自动分析日志并给出可执行的建议
- **自动更新** —— 启动时检查新版本

## 下载

前往 [Releases](https://github.com/Skiewoy/MyLauncher/releases/latest) 下载 `MyLauncher.exe`。

## 系统要求

| 项目 | 要求 |
|---|---|
| 系统 | Windows 10 / 11（64 位） |
| 运行时 | .NET 10 桌面运行时 |
| 其他 | WebView2（Win11 自带，Win10 首次启动会自动安装） |

如果缺少.NET 运行时 启动器将无法打开

## 常见问题

**Q：启动器打不开 / 一闪而过？**

缺少 .NET 10 桌面运行时 需要下载安装 [.NET Desktop Runtime](https://dotnet.microsoft.com/zh-cn/download/dotnet/10.0) 

**Q：游戏启动失败？**

启动器会自动弹出崩溃诊断，里面有具体原因和建议 也可以查看 `%APPDATA%\MyLauncher\launchdiag.txt` 但可能会遇上bug需要提交崩溃反馈

**Q：数据存在哪？**

`%APPDATA%\MyLauncher` 更新启动器不会影响账号和设置

**Q：怎么反馈问题？**

到 [Issues](https://github.com/Skiewoy/MyLauncher/issues) 提交，附上 `launchdiag.txt` 里的日志

## 致谢

感谢 Mojang 提供的游戏，以及所有开源社区的项目

## 申明

代码完全由原创开发三个月所写，请勿用于商用，目前仍有许多问题请友善包容并及时与我反馈，谢谢
