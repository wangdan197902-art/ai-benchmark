---
title: "Claude 3 Haiku vs Claude 3 Sonnet：基准对比"
description: "详细对比 Claude 3 Haiku 与 Claude 3 Sonnet 的基准表现、定价、上下文窗口与合规性。"
date: 2024-03-07
lastmod: 2024-03-07
draft: false
weight: 10
comparison_id: "claude-3-haiku-vs-claude-3-sonnet"
models: ["claude-3-haiku", "claude-3-sonnet"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "anthropic", "anthropic"]
---

# Claude 3 Haiku 对比 Claude 3 Sonnet

## 模型概述

Claude 3 Haiku 与 Claude 3 Sonnet 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Anthropic / Anthropic | 2024-03-07 / 2024-03-04 | 200K / 200K | Proprietary / Proprietary |

## 基准测试表现

| 基准 | Claude 3 Haiku | Claude 3 Sonnet | 胜出 |
|------|------|------|--------|
| ARC | 94.3 | 94.8 | B |
| BBH (BIG-Bench Hard) | 75.7 | 76.1 | Tie |
| GPQA | 44.4 | 35.9 | A |
| GSM8K (Grade School Math 8K) | 82.2 | 84.0 | B |
| HumanEval | 69.4 | 74.5 | B |
| IFEval | 70.8 | 74.3 | B |
| MATH | 52.2 | 42.4 | A |
| MMLU (Massive Multitask Language Understanding) | 77.9 | 81.5 | B |
| MUSR | 58.1 | 64.1 | B |
| WinoGrande | 84.8 | 83.8 | A |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Claude 3 Haiku

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。

### Claude 3 Sonnet

- ✅ MMLU 得分 81.5，知识推理能力强。
- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

Claude 3 Haiku 与 Claude 3 Sonnet 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Claude 3 Haiku 文档地址](https://docs.anthropic.com/claude/docs)
- [Claude 3 Sonnet 文档地址](https://docs.anthropic.com/claude/docs)
