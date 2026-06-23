# 发布说明

这个仓库由 ClawHub 上的 `@staroldtrace/guard-dog` Skill 迁移整理而来。

## 来源

- ClawHub 页面: https://clawhub.ai/staroldtrace/guard-dog
- ClawHub 安装命令: `openclaw skills install @staroldtrace/guard-dog`
- 迁移版本: `2.1.3`

## GitHub 仓库结构

```text
.
├── .codex-plugin/
│   └── plugin.json
├── skills/
│   └── guard-dog/
│       ├── SKILL.md
│       ├── README.md
│       ├── skill-card.md
│       ├── _meta.json
│       └── references/
│           ├── attack-patterns.md
│           └── iron-rules.md
├── LICENSE
├── PUBLISH.md
└── README.md
```

## 校验

发布前应检查：

- `.codex-plugin/plugin.json` 可通过 Codex 插件校验。
- `skills/guard-dog/SKILL.md` 可通过 Skill 快速校验。
- `README.md` 中的版本号与 `SKILL.md` frontmatter 保持一致。
