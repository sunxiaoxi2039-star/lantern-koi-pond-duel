# Lantern Koi Pond · 四家同题对比

同一份任务文本（[PROMPT.txt](PROMPT.txt)），让四家 AI 模型各写一个单文件 Three.js 页面：中式园林夜间锦鲤池，能投放生物，还能导出 .glb 模型和精灵图。

在线看：https://sunxiaoxi2039-star.github.io/lantern-koi-pond-duel/

| 目录 | 模型 / 运行方式 |
|---|---|
| `opus-5.5/` | Claude Opus 5.5 · Claude Code |
| `kimi-k3/` | Kimi K3 · agent 模式 |
| `deepseek-v4.1/` | DeepSeek V4.1-Flash · 单次 API（黑屏，保留原样） |
| `deepseek-v4.1-dsh/` | DeepSeek V4.1-Flash · dsh agent |
| `deepseek-v4.1-dsh-goal/` | DeepSeek V4.1-Flash · dsh /goal 循环 |
| `astra/` | GPT-6-Astra · Codex agent |

各家 `index.html` 都是模型原样输出，没有手工修改。截图保留各自验收时的原始比例。
