# Lemo-Opuscar 短片风格工具箱（Skill 包）

将 AI 写作代理变成一支微型制片组：选定风格、带上故事，代理用代码完成导演、作画、配乐与混音——**不需要视频生成模型，不需要现成素材**。

本 Skill 包是对 [lemomo-ai/lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar)（作者 Lemomo / @lemomo_ai）公开方法的方法论提炼，包含：

- `SKILL.md` — 定义、适用场景、执行步骤、使用说明
- `references/style-catalog.md` — 51种风格全目录（10大类）+ 新增8种实证影像风格
- `references/evidence-films.md` — 实证影像风格详解（数据纪律）
- `references/workflow.md` — 制片工作流与改编玩法
- `assets/quick-ref.md` — 安装/更新/选风格速查
- `usage-examples.md` — 16条可直接复制的使用示例
- `icon.png` — 技能图标

## 快速开始

```sh
claude plugin marketplace add lemomo-ai/lemo-opuscar
claude plugin install lemo-opuscar@lemolab
```

然后直接说需求："做一支45秒水彩风格短片，主题是……"

## 许可

本包为方法论提炼文档（原创语言），核心事实源自原仓库 MIT 文档与作者公开推文；实际制片请安装原仓库。你的成片归你所有。
