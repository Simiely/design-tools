# CHANGELOG.md · 仓库级变更

## 仓库 · 2026-11-19 · 升级 repo-kit 2.9.0

- kit 2.8.0 → **2.9.0**；`schema/kit.lock.json` 重写（`spec_version` 2.1.3 → **2.1.4**）
- 新增能力：`AGENTS_TOO_LONG`（`AGENTS.md` > 150 行报 ERROR）。本仓 `AGENTS.md` 现 21 行，升级当天零拦截
- 2.8.1 起 `check_spec` 只比主/次版本，补丁差异（2.1.3↔2.1.4）不再报错
- `schema/taxonomy.json` 的 `version` 同步为 2.9.0（避免 `skew: taxonomy-vs-lock`）；
  仓库自有配置（`include` / `frontmatter_exempt` / `generated_files`）**未改**
- 补记：本仓 2026-11-18 已接入机器层（repo-kit 2.8.0 / spec 2.1.3），当时**未在 CHANGELOG 记录**，此处一并补上
- 验收：`REPO CHECK: PASS`、`KIT LOCK: PASS (v2.9.0, spec=2.1.4)`

## 仓库 · 2026-10-09 · 新增部署包 `video-launcher`

- 「📦 部署包」分类新增 1 项：`video-launcher`（视频方案启动器 · Python + Tkinter GUI，零第三方依赖）
- 说明：一个窗口拉起 ComfyUI 服务，并驱动 FlashVSR / SeedVR2 视频放大与 MiniMax H3 生成
- 该仓库已发布 `v1.0.0`，exe 走 Releases；索引表「最近更新」记 2026-10-09

## 仓库 · 2026-10-09 · 新增「设计资源 / 实验」分类

- 新增分类「🖼️ 设计资源 / 实验」，收录 5 项：`procedural-drawing-lab` · `web-effects-lab` ·
  `dark-design-style-guide` · `design-tips` · `christmas-tree-storyboard`🔒
- 「说明」区补充新索引入口：`docker-tools` · `knowledge-hub`

## 仓库 · 2026-10-09 · 建库

### 建库

- 建立索引仓库（纯文档、零代码），收录下列项目：
- 收录：SketchUp / 3ds Max 插件、本地视频/模型处理部署包

