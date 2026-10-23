# 快速参考（Quick Ref）

## 安装

```sh
# Claude Code（推荐）
claude plugin marketplace add lemomo-ai/lemo-opuscar
claude plugin install lemo-opuscar@lemolab

# 其他 Agent：复制 plugin/skills/lemo-opuscar/ 到该 Agent 的 skills 目录
# 或直接 clone：
git clone https://github.com/lemomo-ai/lemo-opuscar.git
```

## 常用指令模板

```
做一支 [时长] [风格] 风格的短片，主题是 [主题]，[旁白/音乐偏好]。
改一下 [风格] 风格，改成我自己的版本，叫 [名字]。
用我的 [个人风格名] 做一支 [时长] 的短片，主题是 [主题]。
```

## 一句话选风格

- 快讯/数据 → 字幕新闻 · 数据叙事
- 复盘/辟谣 → 视觉调查 · 档案灯台
- 工程/地理 → 工程简报板 · 卫星简报
- 产品发布 → 暗色发布 · 玻璃渲染
- 温情故事 → 水彩 · 蜡笔 · 水墨

## 更新/卸载

```sh
claude plugin marketplace update lemolab && claude plugin update lemo-opuscar@lemolab
claude plugin uninstall lemo-opuscar@lemolab   # 再手动删 ~/lemo-opuscar
```

个人风格目录 `~/lemo-my-styles/` 不受更新/卸载影响。

## 关键路径

- 共享风格库：`~/lemo-opuscar`
- 个人风格库：`~/lemo-my-styles/<名字>/`
- 官方展示页：https://lemomo-ai.github.io/lemo-opuscar/
- OPUSCAR 98 风格 JSON：https://lemomo-ai.github.io/lemo-opuscar/opuscar98/styles.json

## 许可速记

- 你做的影片：归你，无需署名
- 样片/静帧：CC BY 4.0（署名 LemoLab + 链接 + 说明改动）
- 代码/文档：MIT
