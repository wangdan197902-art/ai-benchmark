---
title: "Gemma 2 9B vs Gemma 7B：基准对比"
description: "详细对比 Gemma 2 9B 与 Gemma 7B 的基准表现、定价、上下文窗口与合规性。"
date: 2024-06-27
lastmod: 2024-06-27
draft: false
weight: 10
comparison_id: "gemma-2-9b-vs-gemma-7b"
models: ["gemma-2-9b", "gemma-7b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "google", "google"]
---

# Gemma 2 9B 对比 Gemma 7B

## 模型概述

Gemma 2 9B 与 Gemma 7B 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Google / Google | 2024-06-27 / 2024-02-21 | 8K / 8K | Gemma License / Gemma License |

## 基准测试表现

| 基准 | Gemma 2 9B | Gemma 7B | 胜出 |
|------|------|------|--------|
| ARC | 90.3 | 88.4 | A |
| BBH (BIG-Bench Hard) | 66.7 | 65.7 | A |
| GPQA | 30.3 | 37.1 | B |
| GSM8K (Grade School Math 8K) | 64.3 | 63.6 | A |
| HumanEval | 60.9 | 61.0 | Tie |
| IFEval | 64.3 | 66.9 | B |
| MATH | 28.9 | 25.7 | A |
| MMLU (Massive Multitask Language Understanding) | 64.3 | 69.6 | B |
| MUSR | 44.1 | 36.2 | A |
| WinoGrande | 72.5 | 74.1 | B |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Gemma 2 9B

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 8K 偏小。

### Gemma 7B

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 8K 偏小。

## 编辑点评

Gemma 2 9B 与 Gemma 7B 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Gemma 2 9B 文档地址](https://ai.google.dev/gemma/docs)
- [Gemma 7B 文档地址](https://ai.google.dev/gemma/docs)
