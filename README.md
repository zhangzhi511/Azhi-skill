# Azhi Skill Collection

<p align="center">
  <a href="#english"><img alt="Read in English" src="https://img.shields.io/badge/English-Read-blue"></a>
  <a href="#中文"><img alt="阅读中文" src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87-%E9%98%85%E8%AF%BB-red"></a>
</p>

<details open>
<summary><strong>English</strong></summary>

## English

## Purpose

This public repository is used to collect, version, and share the SKILL files I create for AI agents and automation workflows.

## Repository Layout

```text
.
├── README.md
├── skills/
│   └── README.md
└── templates/
    └── SKILL_TEMPLATE.md
```

## How To Add A Skill

1. Create a new folder under `skills/`.
2. Add a `SKILL.md` file inside that folder.
3. Include any supporting scripts, examples, or templates next to the skill.
4. Update `skills/README.md` with a short description and usage notes.

Recommended structure:

```text
skills/
└── my-skill/
    ├── SKILL.md
    ├── scripts/
    ├── examples/
    └── templates/
```

## Notes

- Keep each skill self-contained.
- Prefer clear trigger conditions and concrete workflows.
- Add examples when a skill has non-obvious behavior.
- Do not include private tokens, credentials, or sensitive local paths.

</details>

<details>
<summary><strong>中文</strong></summary>

## 中文

## 用途

这个公开仓库用于收集、版本管理和分享我为 AI Agent 与自动化工作流制作的 SKILL 文件。

## 仓库结构

```text
.
├── README.md
├── skills/
│   └── README.md
└── templates/
    └── SKILL_TEMPLATE.md
```

## 如何添加一个 Skill

1. 在 `skills/` 目录下创建一个新的 skill 文件夹。
2. 在该文件夹中添加 `SKILL.md`。
3. 将相关脚本、示例或模板放在同一个 skill 文件夹内。
4. 在 `skills/README.md` 中补充简短说明和使用备注。

推荐结构：

```text
skills/
└── my-skill/
    ├── SKILL.md
    ├── scripts/
    ├── examples/
    └── templates/
```

## 注意事项

- 每个 skill 尽量保持自包含。
- 触发条件和执行流程要写清楚。
- 行为不直观的 skill 建议补充示例。
- 不要提交私密 token、账号凭证或敏感本地路径。

</details>
