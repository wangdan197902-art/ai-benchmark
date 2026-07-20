---
title: "Mistral Large 2 vs Mistral Large：基准对比"
description: "详细对比 Mistral Large 2 与 Mistral Large 的基准表现、定价、上下文窗口与合规性。"
date: 2024-07-24
lastmod: 2024-07-24
draft: false
weight: 10
comparison_id: "mistral-large-2-vs-mistral-large"
models: ["mistral-large-2", "mistral-large"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "mistral", "mistral"]
---

# Mistral Large 2 对比 Mistral Large

## 模型概述

Mistral Large 2 与 Mistral Large 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Mistral / Mistral | 2024-07-24 / 2024-02-26 | 128K / 32K | Mistral Research License / Apache 2.0 |

## 基准测试表现

| 基准 | Mistral Large 2 | Mistral Large | 胜出 |
|------|------|------|--------|
| ARC | — | 93.3 | B |
| BBH (BIG-Bench Hard) | 81.0 | 76.7 | A |
| GPQA | — | 38.1 | B |
| GSM8K (Grade School Math 8K) | 93.0 | 80.9 | A |
| HumanEval | 92.0 | 73.4 | A |
| IFEval | — | 75.8 | B |
| MATH | 71.0 | 49.3 | A |
| MMLU (Massive Multitask Language Understanding) | 84.0 | 82.0 | A |
| MUSR | — | 52.1 | B |
| WinoGrande | — | 83.3 | B |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Mistral Large 2

- ✅ MMLU 得分 84.0，知识推理能力强。
- ✅ HumanEval 92.0，代码生成能力出色。
- ✅ GSM8K 93.0，数学推理稳健。
- ⚠️ 闭源专有模型，不支持自托管。

### Mistral Large

- ✅ MMLU 得分 82.0，知识推理能力强。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

Mistral Large 2 与 Mistral Large 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Mistral Large 2 文档地址](https://docs.mistral.ai/)
- [Mistral Large 文档地址](https://docs.mistral.ai/)
