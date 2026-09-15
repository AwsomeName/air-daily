# 配图说明与事实依据

日期：2026-09-13。使用内置 image_gen 工具生成，共三张；未使用 CLI/API 回退。全部为 AI 效果图，非真实应用截图。原始生成图原样复制，未裁切或修图。

## 配图顺序

1. [01-工作台封面.png](01-工作台封面.png)
2. [02-写作协作效果图.png](02-写作协作效果图.png)
3. [03-本地与远程效果图.png](03-本地与远程效果图.png)

用于介绍产品布局、写作协作场景、本地与可选远程能力边界。所有示例界面、任务文字及状态均为设计内容，不构成运行证据。

## 文案事实依据

核对源码提交：`77e7ce9bcca7c95b6938d678c92184c7e45ddcdd`。本次仅制作介绍与图片，没有重新运行应用验收。

- 主项目 `AGENTS.md` 与 `docs/architecture.md`：单一桌面 App、本地免费免登录、可选远程域与权限边界。
- `package.json`：项目名称、GPL-3.0-only 许可证和源码地址。
- `docs/features/article-platform-publishing.md`：2026-09-08 知乎指定三图文章提交及公开页核验、CSDN 三图审核未通过的记录。
- `docs/features/article-publishing-observable-execution-development-plan.md`：真实执行细步骤与验收限制。
- 目录和行文参考相邻 `AIR/README.md`、`AIR/2026-09-09/发布文案.md` 与 `AIR/2026-09-11/发布文案.md`。

主项目 README 部分历史定位与当前架构不一致，本文定位以 AGENTS.md 和架构文档为准。未编造开发天数、用户量、效率数据或本次功能实测结果。

## 完整生成提示词

### 01-工作台封面.png

```text
Use case: ui-mockup. Asset type: Chinese developer diary introductory cover, portrait 3:4, high resolution. Create a premium editorial product concept poster for CCLink Studio, a local-first desktop AI workbench. Exact main title "CCLink Studio", exact Chinese subtitle "把工作现场，交给 AI 一起参与". Small top label "研发日记 · 初次见面". Centerpiece is a large elegant floating desktop application window, dark graphite VSCode-inspired layout, left file explorer, center markdown document editor with a small browser tab, right Agent chat panel, slim terminal along bottom. Realistic readable hierarchy but minimal small text. Use only neutral demo file names README.md, notes.md and simple code-like lines. Under window three clear text labels "本地工作区" "内嵌浏览器" "Agent 协作". Deep navy background, subtle cyan accents, sophisticated restrained lighting, flat readable typography, generous margins, no robots, no fake statistics, no success claims. Footer exact visible "AI 生成效果图 · 非实机截图". This is a conceptual design, not an actual screenshot.
```

### 02-写作协作效果图.png

```text
Use case: ui-mockup. Asset type: Chinese developer diary scene illustration, portrait 3:4 high resolution. A refined editorial poster for CCLink Studio. Main heading exact "查资料、写文档，在同一个工作台". Small brand above "CCLink Studio". Main image is a front-facing dark graphite desktop app interface in a light mist-grey editorial frame, occupying most of composition. Left slim local file explorer with notes.md and article.md. Main central split panes: a neutral web research page with article cards and a markdown document editor displaying Chinese title "我的项目介绍", brief abstract text and image placeholder. Right Agent panel with short exact demo instruction "把资料整理成初稿" and status "等待审阅". Bottom modest terminal area. Use crisp plausible desktop UI proportions, cyan accent, precise alignment, no invented platform brands, no published success badge. Below image three numbered editorial captions "01 查阅资料" "02 整理初稿" "03 人工审阅". Footer exact "AI 生成效果图 · 内容与界面为设计示例". No robot, no holograms, no charts. Visual communicates the desired collaboration workflow, not verified autonomous completion.
```

### 03-本地与远程效果图.png

```text
Use case: infographic-diagram. Asset type: Chinese developer diary product boundary poster, portrait 3:4 high resolution. Premium editorial design consistent with a dark graphite and cyan CCLink Studio developer workbench. Heading "一个 Studio，从本地开始". Small brand "CCLink Studio". Large primary rounded panel titled "本地能力 · 免费免登录", with an elegant desktop workbench illustration and six clean icon-label tiles: "工作区", "浏览器", "Markdown", "Agent", "Terminal", "数据源". A small physical Android phone illustration connected by cable beneath these tiles, label "Android 真机". Separate smaller secondary panel below connected with a dotted cyan line, title "CCLink 远程入口 · 按需登录", simple distant computer icon, secondary line "需配置并连接在线 Agent". Small footnote above footer "模型服务由用户自行配置". Graphite panels on soft light grey background, restrained mint cyan accents, generous space, impeccable readable Chinese typography. Do not show login blocking the primary local panel, payment icons, cloud-only workbench, robots, extra unsupported abilities or checked successful remote connection. Footer exact "AI 生成效果图 · 非实机截图".
```

