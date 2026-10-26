# 锦囊 发布仓库 (Releases)

锦囊：多个 AI CLI Agent、多台电脑共用一份记忆。

本仓库专用于发布「锦囊完整版（桌面应用）」与「锦囊 Lite（轻量命令行版）」的安装包与更新文件。

---

## 1. 锦囊 完整版（桌面端）

### 下载与安装
从本仓库右侧 [Releases](../../releases) 页面下载最新版 Windows 单文件安装包：
\Jinnang-Setup-<版本>.exe\

双击即可安装到当前用户环境（按用户安装，无需管理员权限）。

> **Windows SmartScreen 提示**：从网上下载的安装包未购买商业签名，Windows 可能弹出「已保护你的电脑」提示，点击「更多信息」→「仍要运行」即可正常安装。

安装完成后自动创建桌面与开始菜单快捷方式，首次启动提供清晰的引导向导。

---

## 2. 锦囊 Lite（命令行轻量版）

适合 Linux、macOS 或偏好纯命令行同步环境的用户。

### 下载与安装
从 [Releases](../../releases) 页面下载：
\jinnang-lite-<版本>.tar.gz\

解压后在终端（Windows 上在 Git Bash）中运行：
\\\ash
tar -xzf jinnang-lite-<版本>.tar.gz
bash setup.sh
\\\

按照勾选式向导提示即可完成接入。

---

## 校验和
每个 Release 均附带 \SHA256SUMS\ 文件供校验文件完整性。
