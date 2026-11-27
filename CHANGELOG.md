# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

---

## [Unreleased]

- 新增子模块：`data/profile` → quanttide-profile-of-game-development（游戏研发档案），首收 qtgame-tycoon 的 TapTap 上架资料（商店文案、素材规格、资质事实、包体与分发）
- bump `apps/qtgame-tycoon` → **v0.1.1**：一套源码多平台发布（`npm run build` 官网 / `build:xhs` 小红书 zip / `build:taptap`），移除 4399 渠道文案，小红书容器适配合入；GitHub Release [v0.1.1](https://github.com/quanttide/qtgame-tycoon/releases/tag/v0.1.1)
- 新增子模块：`data/library` → quanttide-library-of-game-development（量潮游戏研发图书馆），首收 `taptap/` 上架参考（H5 小游戏通道、流程、资质、物料、包体与 MCP 工具）与《TapTap 认证申请公函》模板
- 挂载既有仓：`apps/qtgame-love` → qtgame-love（量潮恋爱游戏，以 fiction 为原型、创始人已授权公司）
- 挂载既有仓：`apps/qtgame-tycoon` → qtgame-tycoon（量潮模拟经营游戏）、`apps/qtgame-war` → qtgame-war（量潮战旗游戏，与兵旗推演域双挂）
- 注册业务入口：`apps/qtgame` → qtgame（量潮游戏业务入口，React 网站）
- 初始化领域仓库；data/ 与 docs/ 资产暂未创建。
