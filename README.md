# Master Cat（大师猫）

Master Cat is an Agent Skill for diagnosing recurring human–AI collaboration problems and turning verified lessons into practical, reusable capabilities.

大师猫从四层处理 AI 协作问题：

1. 辨阴阳：厘清人和 AI 应保留的责任与主体性；
2. 察气脉：查找信息、工具、反馈和交付结果之间的断点；
3. 悟心法：提炼能够跨相邻场景成立的稳定原则；
4. 授一招：在真实对象上采取最小、可验证、可撤回的改善行动。

它属于 Three Cats 协作体系，同时可以完全独立使用。独立使用时不会要求家猫、社交猫或本地接力程序；只有输入明确要求 Three Cats 回条时，才会输出机器可读回条。

## Install

```bash
npx skills add ewanyuan/master-cat-skill
```

技能入口位于：

```text
skills/master-cat/SKILL.md
```

## Example prompts

- `请使用大师猫分析这份 AI 协作观察，不要默认观察者的判断正确。`
- `我反复需要替 AI 做最终质检，帮我判断问题是否真实，以及应该怎样改变。`
- `把这次有效的纠偏经验变成可复用能力，但先判断是否值得封装。`

## Three Cats integration

当上游明确要求回条时，大师猫会在自然语言答复后输出 `THREE_CATS_MASTER_REPLY`。普通独立调用不会输出该协议。

## Status

This repository contains the public edition of the skill. It excludes no core reasoning capability and keeps the optional Three Cats integration protocol.
