# 善识营养配餐 · 更新发布仓库

本仓库**仅**存放 Release 产物（安装包、更新清单）

| 资产 | 用途 |
| --- | --- |
| `latest.json` | tauri v2 更新清单，客户端匿名拉取 `releases/latest/download/latest.json` |
| `善识营养配餐_<版本>_x64_zh-CN.msi` | Windows 安装包 |
| `*.msi.sig` | 对应的 minisign 签名（客户端在 Rust 侧验签） |
