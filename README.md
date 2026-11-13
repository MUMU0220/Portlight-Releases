# Portlight 安装包与自动更新

此仓库仅分发 Portlight 安装包、更新签名和版本清单，不包含应用源码。

当前已发布 **0.1.2 免费签名测试版**，支持 macOS Apple Silicon 与 Windows x64 安装版。[下载当前版本](https://github.com/MUMU0220/Portlight-Releases/releases/latest)。

首次使用自动更新，需要先手动安装 0.1.2 安装版。后续在「设置 → 软件更新」检查、下载并确认安装；首次安装 0.1.2 后显示已是最新版本属于正常结果，待后续版本发布后才会发现新版本。Windows 便携版不执行安装更新。

两个平台的更新包均使用同一把长期 updater 密钥签名，客户端会校验签名及版本。应用、macOS 卷图标和 Windows 安装器使用 Portlight 自有图标。

macOS 采用免费的 ad-hoc 代码签名，未经过 Apple Developer ID 签名或公证，首次打开可能需要在系统设置的「隐私与安全性」允许。已完成隔离测试包的篡改拒绝、下载、安装、重启和数据保留验证。Windows 已完成构建与静态资源、图标及依赖验证，实机安装及跨版本升级仍待验收。本版本用于测试反馈，验收范围见发布说明。

公开更新清单位于 Releases 的 `latest.json`，不需要 GitHub 登录。应用源码继续保存在私有仓库。
