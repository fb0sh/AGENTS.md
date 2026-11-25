# Universal Agent Guidelines

一套轻量、通用的 AI Agent 行为准则，旨在让 Agent **思考更严谨、执行更高效、修改更精准、回答更简洁**。

灵感来源：[Andrej Karpathy](https://x.com/karpathy/status/2015883857489522876)。

## 使用方法

将 [`AGENTS.md`](./AGENTS.md) 放入 Agent 支持的指令目录，或将其内容添加到全局 Instructions 中。

```bash
mkdir -p ~/.agents && curl -fL \
  -H "Accept: application/vnd.github.raw+json" \
  "https://api.github.com/repos/fb0sh/AGENTS.md/contents/AGENTS.md" \
  -o ~/.agents/AGENTS.md
```

## 完整规则

详见 **[AGENTS.md](./AGENTS.md)**。

## License

MIT
