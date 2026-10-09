# design-tools · 设计 / 3D 工具索引

> 🔖 **本仓库是索引仓库（导航中心），不放任何代码。**
> 每个工具/方案的**开发、构建、发行**都在它**自己的独立仓库**里进行 —— 点下表链接直达。

## 工具一览

### 🎨 插件 / 脚本（宿主软件的扩展）

| 工具 | 说明 | 宿主 | 技术栈 | 最新版本 | 最近更新 |
|---|---|---|---|---|---|
| **[`sketchup-material-tools`](https://github.com/Simiely/sketchup-material-tools)** | SketchUp 插件集：按材质合并实体（减体积）+ 导出到 Blender（贴图转英文 / 保留实例 DAE） | SketchUp | Ruby | [`v1.0.0`](https://github.com/Simiely/sketchup-material-tools/releases/latest) | 2026-08-15 |
| **[`vray-material-replacer`](https://github.com/Simiely/vray-material-replacer)** | 批量把 V-Ray 材质替换为 Standard / Physical，并导出材质构成（AI 友好 Markdown） | 3ds Max | MAXScript | — | 2026-08-15 |

### 📦 部署包（本地部署 / 工作流方案）

| 项目 | 说明 | 技术栈 | 最近更新 |
|---|---|---|---|
| **[`video-upscale-deploy`](https://github.com/Simiely/video-upscale-deploy)** | 本地视频放大部署包：Video2X / FlashVSR / SeedVR2 三套可执行方案（12G / 16G / 24G 显卡） | PowerShell | 2026-09-30 |
| **[`seedvr2-local-deploy`](https://github.com/Simiely/seedvr2-local-deploy)** | SeedVR2 本地部署（RTX 4070S 12GB）· 单项目四件套规范文档 | — | 2026-08-26 |
| **[`minimax-h3-local-deploy`](https://github.com/Simiely/minimax-h3-local-deploy)** | MiniMax H3 本地部署说明（12GB / 16GB 消费级显卡） | Batchfile | 2026-09-30 |

### 🖼️ 设计资源 / 实验

| 项目 | 说明 | 技术栈 | 在线阅读 | 最近更新 |
|---|---|---|---|---|
| **[`procedural-drawing-lab`](https://github.com/Simiely/procedural-drawing-lab)** | 程序化作图前哨实验场：纯前端零依赖单 HTML，绘制生成式图形 + 参数面板实时调参 | HTML · JS | 🔗[页面](https://simiely.github.io/procedural-drawing-lab/) | 2026-09-22 |
| **[`web-effects-lab`](https://github.com/Simiely/web-effects-lab)** | Web 效果实验场：纯前端动效与交互演示集合（零依赖单 HTML） | HTML · JS | — | 2026-08-13 |
| **[`dark-design-style-guide`](https://github.com/Simiely/dark-design-style-guide)** | 深色设计风格收集：28 种深色风格主页设计方案手册（布局 / 组件 / 色板 / CSS 变量） | HTML · CSS | 🔗[页面](https://simiely.github.io/dark-design-style-guide/) | 2026-08-15 |
| **[`figma-navigation-tips`](https://github.com/Simiely/figma-navigation-tips)** | Figma 使用技巧速查：文档内导航跳转 + 评论排布等实战技巧 | — | — | 2026-08-25 |
| `christmas-tree-storyboard` 🔒 | 水晶圣诞树宣传片分镜方案 · A 经典展示 / B 迪士尼式揭示 / C 融合 | — | — | 2026-09-10 |

## 说明

- **一个项目一个仓库**：源码、Issue、Releases 都在各自仓库；本仓库只负责**索引与导航**；
- **为什么不归档**：这些仓库还在独立迭代、发布，归档后 Releases 亦变只读（发不了新版），
  因此统一为「各仓库独立 + 本仓做索引」；
- **与其它索引的分工**：PC 端常驻程序/系统工具见 [`pc-tools`](https://github.com/Simiely/pc-tools)，
  移动端 App 见 [`mobile-apps`](https://github.com/Simiely/mobile-apps)，
  技术文档/教程见 [`tech-guides`](https://github.com/Simiely/tech-guides)，
  自建服务见 [`docker-tools`](https://github.com/Simiely/docker-tools)，
  知识库/资料见 [`knowledge-hub`](https://github.com/Simiely/knowledge-hub)。
- 文档规范遵循 [knowledge-base 单项目规范](https://github.com/Simiely/knowledge-base)。

## 相关仓库

- 宿主软件插件集合（总管仓库）：[`ae-tools`](https://github.com/Simiely/ae-tools)（After Effects）· [`blender-addons`](https://github.com/Simiely/blender-addons)（Blender）· [`c4d-tools`](https://github.com/Simiely/c4d-tools)（Cinema 4D）
