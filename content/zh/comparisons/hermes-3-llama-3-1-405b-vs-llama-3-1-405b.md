---
title: "Hermes 3 Llama 3.1 405B vs Llama 3.1 405B：基准对比"
description: "详细对比 Hermes 3 Llama 3.1 405B 与 Llama 3.1 405B 的基准表现、定价、上下文窗口与合规性。"
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
comparison_id: "hermes-3-llama-3-1-405b-vs-llama-3-1-405b"
models: ["hermes-3-llama-3-1-405b", "llama-3-1-405b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "meta"]
---

# Hermes 3 Llama 3.1 405B 对比 Llama 3.1 405B

## 模型概述

Hermes 3 Llama 3.1 405B 与 Llama 3.1 405B 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Other / Meta | 2024-08-12 / 2024-07-23 | 131K / 128K | Llama 3.1 Community License / Llama 3 Community License |

## 基准测试表现

| 基准 | Hermes 3 Llama 3.1 405B | Llama 3.1 405B | 胜出 |
|------|------|------|--------|
| ARC | 94.5 | — | A |
| BBH (BIG-Bench Hard) | 82.1 | 82.9 | B |
| GPQA | 40.5 | — | A |
| GSM8K (Grade School Math 8K) | 88.9 | 89.2 | Tie |
| HumanEval | 89.0 | 89.0 | Tie |
| IFEval | 78.2 | — | A |
| MATH | 65.7 | 73.8 | B |
| MMLU (Massive Multitask Language Understanding) | 83.9 | 88.6 | B |
| MUSR | 57.7 | — | A |
| WinoGrande | 86.5 | — | A |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Hermes 3 Llama 3.1 405B

- ✅ MMLU 得分 83.9，知识推理能力强。
- ✅ HumanEval 89.0，代码生成能力出色。
- ✅ GSM8K 88.9，数学推理稳健。
- ⚠️ 闭源专有模型，不支持自托管。

### Llama 3.1 405B

- ✅ MMLU 得分 88.6，知识推理能力强。
- ✅ HumanEval 89.0，代码生成能力出色。
- ✅ GSM8K 89.2，数学推理稳健。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

Hermes 3 Llama 3.1 405B 与 Llama 3.1 405B 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Hermes 3 Llama 3.1 405B 文档地址](https://huggingface.co/models)
- [Llama 3.1 405B 文档地址](https://llama.meta.com/docs/)
