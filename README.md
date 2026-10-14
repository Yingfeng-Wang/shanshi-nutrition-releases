# 善识营养配餐 · 更新发布仓库

本仓库**仅**存放 Release 产物（安装包、更新清单）

| 资产 | 用途 |
| --- | --- |
| `latest.json` | 更新清单：版本号、更新说明、安装包地址、minisign 签名。客户端匿名拉取 `releases/latest/download/latest.json` |
| `ShanshiNutritionPeican_1.0.2_x64_zh-CN.msi` | Windows 安装包（资产名须为纯 ASCII —— GitHub 会整段剔除中文等非 ASCII 字符） |
| `ShanshiNutritionPeican_1.0.2_x64_zh-CN.msi.sig` | 安装包的 minisign 签名。客户端下载后在本地验签，**验签不过即拒绝安装** |


