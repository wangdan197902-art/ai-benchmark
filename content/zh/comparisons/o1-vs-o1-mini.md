---
title: "o1 vs o1 mini：基准对比"
description: "详细对比 o1 与 o1 mini 的基准表现、定价、上下文窗口与合规性。"
date: 2024-12-17
lastmod: 2024-12-17
draft: false
weight: 10
comparison_id: "o1-vs-o1-mini"
models: ["o1", "o1-mini"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "openai"]
---

# o1 对比 o1 mini

## 模型概述

o1 与 o1 mini 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Openai / Openai | 2024-12-17 / 2024-09-12 | 200K / 128K | Proprietary / Proprietary |

## 基准测试表现

| 基准 | o1 | o1 mini | 胜出 |
|------|------|------|--------|
| ARC | 96.8 | 93.7 | A |
| BBH (BIG-Bench Hard) | 83.1 | 77.2 | A |
| GPQA | 57.5 | 40.8 | A |
| GSM8K (Grade School Math 8K) | 88.9 | 86.6 | A |
| HumanEval | 85.3 | 78.0 | A |
| IFEval | 82.2 | 73.1 | A |
| MATH | 55.7 | 44.2 | A |
| MMLU (Massive Multitask Language Understanding) | 86.3 | 78.2 | A |
| MUSR | 71.8 | 54.0 | A |
| WinoGrande | 86.7 | 78.3 | A |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### o1

- ✅ MMLU 得分 86.3，知识推理能力强。
- ✅ HumanEval 85.3，代码生成能力出色。
- ✅ GSM8K 88.9，数学推理稳健。
- ⚠️ 闭源专有模型，不支持自托管。

### o1 mini

- ✅ GSM8K 86.6，数学推理稳健。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

o1 与 o1 mini 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [o1 文档地址](https://platform.openai.com/docs/models)
- [o1 mini 文档地址](https://platform.openai.com/docs/models)
