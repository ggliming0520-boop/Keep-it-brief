# Keep it brief

防发散计划协作模式。

这个 skill 适合在你想法很多、需要先做计划、不想被 AI 的解释和发散带跑时使用。

## 它能做什么

- 保持当前计划可见。
- 一次只推进一个问题。
- 用户有新想法时先暂存为灵感。
- 旧计划没完成前，不直接开启新计划。
- 当前计划完成后，再回看灵感和后续计划。

## 安装

推荐：

```bash
npx skills add ggliming0520-boop/Keep-it-brief
```

手动安装：

```bash
git clone https://github.com/ggliming0520-boop/Keep-it-brief.git "%USERPROFILE%\.codex\skills\keep-it-brief"
```

安装后重启 Codex。

## 快速开始

显式触发：

```text
$keep-it-brief
用 Keep it brief 模式
```

半自动触发：

```text
帮我梳理想法
先做计划不要行动
继续走主线
```

这类表达会先让 AI 问你是否进入模式。

## 相关文档

- [使用指南](docs/usage-guide.zh-CN.md)
- [负责使用](docs/responsible-use.md)
- [基础流程示例](examples/basic-flow.zh-CN.md)
- [灵感暂存示例](examples/saved-idea-flow.zh-CN.md)
