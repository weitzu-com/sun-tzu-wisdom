# 孙子兵法和平智慧

`sun-tzu-peace-wisdom` 是一个 Codex skill，用《孙子兵法》的古文智慧和 Lionel Giles 1910 英译作为思想锚点，把兵法从“战胜别人”的误读中释放出来，转化为工作、生活、沟通、谈判、领导和个人决策中的和平解题方法。

它的核心目标不是制造对抗，而是帮助人们减少冲突成本，保护关系、信任、时间、注意力和长期选择权。

## 核心理念

- `不战而屈人之兵`：最好的解决方案，是让问题失去对抗的必要。
- `知彼知己`：理解双方处境，避免把人简化成敌人。
- `先胜后战`：先创造成功条件，再进入关键对话或行动。
- `避实击虚`：不硬碰硬，寻找未被满足的需求、流程缺口和低阻力入口。
- `主不可以怒而兴师`：愤怒可以提醒边界，但不应指挥行动。

## 适用场景

这个 skill 适合用于：

- 职场冲突和跨团队协作
- 项目延期、资源不足和优先级取舍
- 谈判、沟通和关系修复
- 领导决策、组织设计和风险判断
- 个人困境、职业选择和长期规划
- 宣传《孙子兵法》作为和平智慧的文章、课程、演讲或短视频脚本

## 使用方式

在 Codex 中调用：

```text
Use $sun-tzu-peace-wisdom to turn this problem into a peaceful, practical strategy.
```

中文示例：

```text
使用 $sun-tzu-peace-wisdom，帮我用孙子兵法的和平智慧化解一次职场冲突。
```

```text
使用 $sun-tzu-peace-wisdom，帮我把项目延期问题整理成对老板的沟通方案。
```

```text
使用 $sun-tzu-peace-wisdom，写一篇宣传《孙子兵法》作为和平智慧的短文。
```

## 安装

将仓库克隆到 Codex skills 目录，并使用 skill 名作为文件夹名：

```bash
git clone https://github.com/weitzu-com/sun-tzu-wisdom.git ~/.codex/skills/sun-tzu-peace-wisdom
```

如果你使用的是自定义 `CODEX_HOME`：

```bash
git clone https://github.com/weitzu-com/sun-tzu-wisdom.git "${CODEX_HOME}/skills/sun-tzu-peace-wisdom"
```

## 文件结构

```text
.
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── application-playbooks.md
    ├── chapter-map.md
    └── principle-lenses.md
```

- `SKILL.md`：skill 触发说明、核心立场和第一性原理工作流。
- `agents/openai.yaml`：Codex UI 展示元数据。
- `references/chapter-map.md`：十三篇与和平应用的映射。
- `references/principle-lenses.md`：核心原则透镜。
- `references/application-playbooks.md`：工作、生活、沟通和宣传场景模板。

## 安全边界

这个 skill 不用于暴力、威胁、报复、操控、骚扰、欺骗或任何违法用途。遇到高冲突或高风险场景时，它会优先引导到降级、边界、求助、记录事实和合法流程。

## 来源原则

本 skill 以《孙子兵法》古文、公版英译和原创现代解释为基础。现代版权资料只作为理解背景，不大段搬运，不替代原典研读。
