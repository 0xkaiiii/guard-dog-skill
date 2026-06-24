# 发布说明

这个仓库由 ClawHub 上的 `@staroldtrace/guard-dog` Skill 迁移整理而来，定位为 **OpenClaw 专用 Skill**。

## 来源

- ClawHub 页面: https://clawhub.ai/staroldtrace/guard-dog
- ClawHub 安装命令: `openclaw skills install @staroldtrace/guard-dog`
- 迁移版本: `2.1.3`

## GitHub 仓库结构

```text
.
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

- `skills/guard-dog/SKILL.md` 保持 OpenClaw/ClawHub 可安装。
- `README.md` 只描述 OpenClaw/ClawHub 安装方式，不加入 Codex 插件安装方式。
- `README.md` 中的版本号与 `SKILL.md` frontmatter 保持一致。
