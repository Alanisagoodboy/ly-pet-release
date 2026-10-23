# 凌玉桌宠 · 发布仓库

本仓库只放**发布产物**，不放源码（源码在私有仓库）。

- `version.json`：当前最新版本信息（桌宠内置的更新检查每 6 小时拉一次这个文件）
- [Releases](https://github.com/Alanisagoodboy/ly-pet-release/releases)：各版本安装包下载

## 下载安装

1. 打开 [最新 Release](https://github.com/Alanisagoodboy/ly-pet-release/releases/latest)，下载 `ly-pet-x.x.x.exe`
2. 双击运行（首次可能弹 SmartScreen：更多信息 → 仍要运行）
3. 想配自己的碎碎念 AI 模型：编辑 `%USERPROFILE%\.ly-pet\config.jsonc`，右键宠物「重载配置」

## 发新版（维护者）

1. 打好新 exe（文件名用 ASCII，如 `ly-pet-0.2.0.exe`）
2. `gh release create v0.2.0 ly-pet-0.2.0.exe --title v0.2.0 --notes "更新说明"`
3. 更新本仓库 `version.json` 的 version / url / notes 并 push
4. 所有已安装用户的桌宠会在下次检查时收到气泡 + 系统通知，一键打开下载页
