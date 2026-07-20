---
title: "GPT-4o mini vs Claude 3.5 Haiku：基准对比"
description: "详细对比 GPT-4o mini 与 Claude 3.5 Haiku 的基准表现、定价、上下文窗口与合规性。"
date: 2024-07-18
lastmod: 2024-07-18
draft: false
weight: 10
comparison_id: "gpt-4o-mini-vs-claude-3-5-haiku"
models: ["gpt-4o-mini", "claude-3-5-haiku"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "anthropic"]
---

# GPT-4o mini 对比 Claude 3.5 Haiku

## 模型概述

GPT-4o mini 与 Claude 3.5 Haiku 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Openai / Anthropic | 2024-07-18 / 2024-11-04 | 128K / 200K | Proprietary / Proprietary |

## 基准测试表现

| 基准 | GPT-4o mini | Claude 3.5 Haiku | 胜出 |
|------|------|------|--------|
| ARC | 93.9 | 91.8 | A |
| BBH (BIG-Bench Hard) | 70.3 | 70.2 | Tie |
| GPQA | 42.6 | 31.1 | A |
| GSM8K (Grade School Math 8K) | 75.1 | 75.5 | Tie |
| HumanEval | 78.0 | 73.8 | A |
| IFEval | 67.9 | 73.6 | B |
| MATH | 51.8 | 53.0 | B |
| MMLU (Massive Multitask Language Understanding) | 79.7 | 77.6 | A |
| MUSR | 53.1 | 52.3 | A |
| WinoGrande | 79.6 | 83.8 | B |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### GPT-4o mini

- ✅ 支持文本、图像、音频多模态输入。
- ⚠️ 闭源专有模型，不支持自托管。

### Claude 3.5 Haiku

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

GPT-4o mini 与 Claude 3.5 Haiku 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [GPT-4o mini 文档地址](https://platform.openai.com/docs/models)
- [Claude 3.5 Haiku 文档地址](https://docs.anthropic.com/claude/docs)
