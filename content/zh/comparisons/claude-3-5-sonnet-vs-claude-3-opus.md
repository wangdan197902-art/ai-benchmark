---
title: "Claude 3.5 Sonnet vs Claude 3 Opus：基准对比"
description: "详细对比 Claude 3.5 Sonnet 与 Claude 3 Opus 的基准表现、定价、上下文窗口与合规性。"
date: 2024-06-20
lastmod: 2024-06-20
draft: false
weight: 10
comparison_id: "claude-3-5-sonnet-vs-claude-3-opus"
models: ["claude-3-5-sonnet", "claude-3-opus"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "anthropic", "anthropic"]
---

# Claude 3.5 Sonnet 对比 Claude 3 Opus

## 模型概述

Claude 3.5 Sonnet 与 Claude 3 Opus 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Anthropic / Anthropic | 2024-06-20 / 2024-03-04 | 200K / 200K | Proprietary / Proprietary |

## 基准测试表现

| 基准 | Claude 3.5 Sonnet | Claude 3 Opus | 胜出 |
|------|------|------|--------|
| ARC | — | 94.5 | B |
| BBH (BIG-Bench Hard) | 84.5 | 81.6 | A |
| GPQA | — | 46.0 | B |
| GSM8K (Grade School Math 8K) | 96.4 | 91.8 | A |
| HumanEval | 92.0 | 83.3 | A |
| IFEval | — | 79.2 | B |
| MATH | 71.1 | 42.7 | A |
| MMLU (Massive Multitask Language Understanding) | 88.7 | 81.2 | A |
| MUSR | — | 53.3 | B |
| WinoGrande | — | 81.9 | B |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Claude 3.5 Sonnet

- ✅ MMLU 得分 88.7，知识推理能力强。
- ✅ HumanEval 92.0，代码生成能力出色。
- ✅ GSM8K 96.4，数学推理稳健。
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

### Claude 3 Opus

- ✅ MMLU 得分 81.2，知识推理能力强。
- ✅ HumanEval 83.3，代码生成能力出色。
- ✅ GSM8K 91.8，数学推理稳健。
- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

Claude 3.5 Sonnet 与 Claude 3 Opus 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Claude 3.5 Sonnet 文档地址](https://docs.anthropic.com/claude/docs)
- [Claude 3 Opus 文档地址](https://docs.anthropic.com/claude/docs)
