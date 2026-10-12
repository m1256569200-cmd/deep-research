# 🔍 deep-research

**Turn your agent into a research analyst. 多源检索、交叉验证的深度调研 — *deep-research is all you need.***

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Skill](https://img.shields.io/badge/skill-Claude%20Code%20%7C%20Cursor%20%7C%20Copilot-blue)

## ✨ What it does

Ask anything — your agent decomposes it into sub-questions, searches multiple independent sources, cross-verifies every claim, and delivers a **structured report with citations**. Conflicts flagged, unknowns admitted, no hallucinated confidence.

```
you: "is Postgres or MySQL better for our analytics workload?"
agent: 📋 plan → 🔎 multi-source search → ✅/⚠️/❓ verification → 📊 cited report
```

## 📦 Install

```bash
# Claude Code
mkdir -p ~/.claude/skills/deep-research && cp SKILL.md ~/.claude/skills/deep-research/

# Cursor (project-level)
mkdir -p .cursor/skills/deep-research && cp SKILL.md .cursor/skills/deep-research/
```

## 🎯 How it works

1. **📋 Decomposes** your question into independently investigable sub-questions
2. **🔎 Searches wide** — docs, papers, primary sources, community (URLs tracked)
3. **⚖️ Cross-verifies** — corroborated / conflicting / uncertain / unknown, labeled
4. **📊 Reports** — TL;DR, findings with `[citations]`, conflicts, gaps, recommendation, sources

## 🧭 Ground rules

- Every factual claim cited — or it's labeled inference/unknown
- Fact vs. inference vs. unknown always distinguished
- Newest authoritative source wins; dated sources flagged

---

## 🇨🇳 中文介绍

**把 agent 变成调研分析师。** 问任何问题，它拆成子问题、多源检索、交叉验证，最后给你一份**带引用的结构化报告**。

- 📋 先拆解问题，列出调研计划
- 🔎 多源检索：官方文档、论文、一手来源、社区讨论
- ⚖️ 交叉验证：多方印证的才敢写，冲突的摆出来，查不到的直接说不知道
- 📊 结构化报告：TL;DR、带引用的结论、冲突点、未知项、建议

适合：技术选型、行业调研、竞品分析、任何"帮我深入研究一下"的场景。

## 📄 License

MIT
