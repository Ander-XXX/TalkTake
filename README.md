# 山非山

山非山（TalkTake）是一套面向内容创作者的 AI 自动导演工具：从拍摄准备、采访提纲到素材整理，帮助你更快地完成一条可发布的视频。

## 下载

当前版本：**v0.1.6**

请前往 [Releases](https://github.com/Ander-XXX/TalkTake/releases) 下载对应平台的安装包：

| 平台 | 安装包 | 适用设备 |
| --- | --- | --- |
| macOS | `ShanFeiShan-0.1.6-macOS-arm64.dmg` | Apple 芯片（M1/M2/M3/M4） |
| Windows | `ShanFeiShan-0.1.6-Windows-x64.zip` | 64 位 Windows |

如果你不确定该下载哪个文件：Apple 芯片 Mac 选择 macOS 版本；Windows 电脑选择 Windows 版本。当前版本不提供 Intel Mac 安装包。

## 安装

### macOS

1. 下载并打开 `ShanFeiShan-0.1.6-macOS-arm64.dmg`。
2. 将「山非山」拖入 **Applications（应用程序）** 文件夹。
3. 从应用程序中启动山非山。

首次打开如果 macOS 提示无法验证开发者，请在 **系统设置 → 隐私与安全性** 中允许打开，然后重新启动应用。

### Windows

1. 下载并解压 `ShanFeiShan-0.1.6-Windows-x64.zip`。
2. 运行解压目录中的安装程序，按向导完成安装。
3. 从开始菜单或桌面快捷方式启动山非山。

如果 Windows Defender 显示安全提示，请确认文件来自本仓库的 [Releases](https://github.com/Ander-XXX/TalkTake/releases) 页面后再继续。

## 版本说明

### v0.1.6

- 首个公开发布版本
- 提供 macOS Apple 芯片和 Windows 64 位安装包

详细变更记录会随每个版本发布同步更新。

## 校验安装包

Release 页面提供每个安装包的 SHA-256 校验值。下载后可按下面的方式核对：

```bash
# macOS
shasum -a 256 ShanFeiShan-0.1.6-macOS-arm64.dmg

# Windows PowerShell
Get-FileHash .\\ShanFeiShan-0.1.6-Windows-x64.zip -Algorithm SHA256
```

计算出的值应与 Release 页面显示的值一致。

## 问题反馈

使用中遇到问题，请在 [Issues](https://github.com/Ander-XXX/TalkTake/issues) 提交反馈，并尽量附上：

- 操作系统及版本
- 山非山版本号
- 复现步骤和完整报错信息

## 许可

本项目的许可协议将在后续版本中补充。未经项目维护者书面许可，请勿将安装包用于再分发或商业售卖。
