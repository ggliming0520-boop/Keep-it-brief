# Keep it brief

防发散计划协作模式 / A Codex skill for keeping planning brief, sequential, and non-distracting.

[中文 README](README.zh-CN.md)

## What it does

`keep-it-brief` helps Codex keep planning conversations on track when ideas are scattered, multi-step work is easy to derail, or the user wants to plan before acting.

It uses a lightweight plan notebook:

```text
Current plan:
Progress:
Current step:
Next step:
Saved ideas:
Confirmed future plans:
```

## Install

Recommended:

```bash
npx skills add ggliming0520-boop/Keep-it-brief
```

Manual install:

```bash
git clone https://github.com/ggliming0520-boop/Keep-it-brief.git "${CODEX_HOME:-$HOME/.codex}/skills/keep-it-brief"
```

Restart Codex after installation.

## Quick start

Explicit trigger:

```text
$keep-it-brief
```

or:

```text
Use Keep it brief mode.
```

Semi-automatic trigger:

```text
Help me organize my ideas.
```

Codex should ask whether you want to enter Keep it brief mode before applying the full workflow.

## More

- [中文使用指南](docs/usage-guide.zh-CN.md)
- [负责使用](docs/responsible-use.md)
- [基础流程示例](examples/basic-flow.zh-CN.md)
- [灵感暂存示例](examples/saved-idea-flow.zh-CN.md)
