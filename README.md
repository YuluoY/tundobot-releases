# 团豆 TundoBot 发布

本仓库只存放团豆桌面应用的安装包与更新清单（GitHub Releases），**不包含源码**。

- 下载：在 [Releases](../../releases/latest) 中下载 `TundoBot-<版本>-darwin-arm64.zip`，解压后把 `TundoBot.app` 拖入“应用程序”。
- 首次打开：应用未经过 Apple 公证，macOS 会拦截。请在“应用程序”中右键 TundoBot →“打开”，或在“系统设置 → 隐私与安全性”中允许一次。
- 更新：已安装的应用会读取 `latest-darwin-arm64.json`，校验 Ed25519 签名与 SHA-512 后一键更新。
- 平台：当前仅提供 macOS（Apple Silicon）。
