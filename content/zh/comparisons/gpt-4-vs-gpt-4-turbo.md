---
title: "GPT-4 vs GPT-4 Turbo：基准对比"
description: "详细对比 GPT-4 与 GPT-4 Turbo 的基准表现、定价、上下文窗口与合规性。"
date: 2023-03-14
lastmod: 2023-03-14
draft: false
weight: 10
comparison_id: "gpt-4-vs-gpt-4-turbo"
models: ["gpt-4", "gpt-4-turbo"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "openai"]
---

# GPT-4 对比 GPT-4 Turbo

## 模型概述

GPT-4 与 GPT-4 Turbo 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Openai / Openai | 2023-03-14 / 2023-11-06 | 8K / 128K | Proprietary / Proprietary |

## 基准测试表现

| 基准 | GPT-4 | GPT-4 Turbo | 胜出 |
|------|------|------|--------|
| ARC | 94.1 | 94.2 | Tie |
| BBH (BIG-Bench Hard) | 80.9 | 78.5 | A |
| GPQA | 39.2 | 49.2 | B |
| GSM8K (Grade School Math 8K) | 91.7 | 85.2 | A |
| HumanEval | 77.6 | 80.5 | B |
| IFEval | 74.6 | 77.9 | B |
| MATH | 43.9 | 50.9 | B |
| MMLU (Massive Multitask Language Understanding) | 85.8 | 84.4 | A |
| MUSR | 54.6 | 61.1 | B |
| WinoGrande | 80.3 | 80.8 | B |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### GPT-4

- ✅ MMLU 得分 85.8，知识推理能力强。
- ✅ GSM8K 91.7，数学推理稳健。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 8K 偏小。

### GPT-4 Turbo

- ✅ MMLU 得分 84.4，知识推理能力强。
- ✅ HumanEval 80.5，代码生成能力出色。
- ✅ GSM8K 85.2，数学推理稳健。
- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 128K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

GPT-4 与 GPT-4 Turbo 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [GPT-4 文档地址](https://platform.openai.com/docs/models)
- [GPT-4 Turbo 文档地址](https://platform.openai.com/docs/models)
