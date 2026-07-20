---
title: "GPT-4o vs o1 Preview：基准对比"
description: "详细对比 GPT-4o 与 o1 Preview 的基准表现、定价、上下文窗口与合规性。"
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
comparison_id: "gpt-4o-vs-o1-preview"
models: ["gpt-4o", "o1-preview"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "openai"]
---

# GPT-4o 对比 o1 Preview

## 模型概述

GPT-4o 与 o1 Preview 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Openai / Openai | 2024-05-13 / 2024-09-12 | 128K / 128K | Proprietary / Proprietary |

## 基准测试表现

| 基准 | GPT-4o | o1 Preview | 胜出 |
|------|------|------|--------|
| ARC | — | 96.0 | B |
| BBH (BIG-Bench Hard) | 83.1 | 84.5 | B |
| GPQA | — | 57.7 | B |
| GSM8K (Grade School Math 8K) | 95.8 | 92.5 | A |
| HumanEval | 90.2 | 90.1 | Tie |
| IFEval | — | 84.4 | B |
| MATH | 76.6 | 71.5 | A |
| MMLU (Massive Multitask Language Understanding) | 88.7 | 85.3 | A |
| MUSR | — | 64.1 | B |
| WinoGrande | — | 85.2 | B |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### GPT-4o

- ✅ MMLU 得分 88.7，知识推理能力强。
- ✅ HumanEval 90.2，代码生成能力出色。
- ✅ GSM8K 95.8，数学推理稳健。
- ✅ 支持文本、图像、音频多模态输入。
- ⚠️ 闭源专有模型，不支持自托管。

### o1 Preview

- ✅ MMLU 得分 85.3，知识推理能力强。
- ✅ HumanEval 90.1，代码生成能力出色。
- ✅ GSM8K 92.5，数学推理稳健。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

GPT-4o 与 o1 Preview 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [GPT-4o 文档地址](https://platform.openai.com/docs/models/gpt-4o)
- [o1 Preview 文档地址](https://platform.openai.com/docs/models)
