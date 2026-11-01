# Chinese Academic Writing · 中文学术写作优化

中文学术论文语言润色 Skill：减少翻译腔、AI 模板化表达、冗余连接词和抽象名词堆砌，提升中文论述的自然度与凝练度，同时保留原意、专业术语、数据与引文。尤其适合医学和中医学术写作。

An AI skill for polishing Chinese academic prose. It reduces translationese, formulaic AI phrasing, redundant connectives, and excessive nominalization while preserving meaning, technical terminology, data, and citations. Particularly suitable for medical and traditional Chinese medicine manuscripts.

## 功能 / Features

- 消除英语式中文和生硬的逻辑衔接 / Reduce translationese and unnatural transitions.
- 精简冗余表达，避免机械句式 / Simplify verbose prose and repetitive templates.
- 保留论点、证据强度、术语和引文 / Preserve claims, evidentiary strength, terminology, and citations.
- 适配中文医学与中医学术语境 / Support medical and traditional Chinese medicine writing.
- 默认直接输出改写稿 / Return revised prose by default.

## 安装 / Installation

将 `SKILL.md` 所在目录复制到支持 Agent Skills 的工具的 skills 目录，具体路径依客户端而定。

Copy this directory into the skills location supported by your Agent Skills-compatible client. The location depends on the client.

例如 / Example:

```bash
git clone https://github.com/whitewatercn/chinese-academic-writing-skill.git
mkdir -p ~/.codex/skills
cp -R chinese-academic-writing-skill ~/.codex/skills/chinese-academic-writing
```

## 使用 / Usage

```text
请使用 chinese-academic-writing 润色下面的中医学术段落，去除翻译腔和 AI 模板化表达，保留原意、术语和引用：
[粘贴正文]
```

```text
Use chinese-academic-writing to refine the following Chinese academic paragraph. Remove translationese and formulaic wording without changing its claims, terminology, or citations:
[Paste text]
```

## 原则 / Principles

本 Skill 只负责语言层面的优化，不替代文献核查、事实核验或同行评审。遇到疑似错误时提示核实，不编造证据或擅改经典原文。

This skill improves writing rather than performing fact-checking or peer review. Suspected errors should be flagged, not silently rewritten.

## 文件 / Files

- `SKILL.md`：技能元数据、触发场景、改写规则和工作流程 / Skill metadata, triggers, editing rules, and workflow.
- `README.md`：中英文使用说明 / Bilingual documentation.

## License

No license has been selected. All rights reserved until the repository owner adds a license.
