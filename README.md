# 开头钩子 Skill（kaitou-gouzi）

这个 Skill 专门写短视频的开头钩子，也就是视频前 2–6 秒。

钩子按四件套一起出：**口播 + 屏幕文字 + 画面 + 音频**，四样必须说同一件事。默认场景是贵阳房产自媒体，其他行业同样能用。

## 能做什么

| 你给它 | 它给你 |
|---|---|
| 一个选题或一段口播稿 | 1 套首推加 4 套备选，覆盖至少 3 种口播结构，附拍剪自检和结尾留资句 |
| 你写好的开头 | 逐项诊断（语境、反差、视角、四件套对齐），指出病因，给 3 版改写 |
| 对标爆款的开头 | 拆出四件套和结构类型，说明为什么火，抽出可复用骨架，换成你的版本 |

## 安装

### Claude Code

```
/plugin marketplace add shi930508/kaitou-gouzi-skill
/plugin install kaitou-gouzi@kaitou-gouzi-skill
```

也可以手动安装：把 `skills/kaitou-gouzi` 文件夹复制到 `~/.claude/skills/` 下。

### Codex、Cursor 等其他 AI Agent

```
npx skills add shi930508/kaitou-gouzi-skill
```

按提示选择要装到哪个 Agent。

如果你的 Agent 不在支持列表里，把 `skills/kaitou-gouzi` 文件夹复制到它读取 Skill 的目录即可。整个 Skill 只有一个 `SKILL.md`，没有脚本和依赖。

### Claude 网页版 / App

1. 在本仓库的 Releases 页面下载 `kaitou-gouzi.zip`
2. 在 Claude 的技能设置里上传这个文件

## 怎么用

装好后直接说需求，不用点名 Skill：

- "帮我写个开头：贵阳刚需首付 30 万，到底选哪个片区"
- "这个开头行不行：大家好我是鹏飞，今天聊聊二手房……"
- "拆一下这个爆款开头为什么火，套到我的升学号上"

只要视频标题、封面大字或金句时，建议配合标题类 Skill 使用。

## 方法论来源

方法论来自 Kallaway 的《短视频钩子工作坊》（Short-Form Hooks Workshop），已按中文短视频和房产场景重新整理。所有示例都是新写的。

## 许可

MIT
