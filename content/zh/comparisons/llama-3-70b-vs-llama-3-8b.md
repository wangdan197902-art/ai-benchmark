---
title: "Llama 3 70B vs Llama 3 8B：基准对比"
description: "详细对比 Llama 3 70B 与 Llama 3 8B 的基准表现、定价、上下文窗口与合规性。"
date: 2024-04-18
lastmod: 2024-04-18
draft: false
weight: 10
comparison_id: "llama-3-70b-vs-llama-3-8b"
models: ["llama-3-70b", "llama-3-8b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "meta", "meta"]
---

# Llama 3 70B 对比 Llama 3 8B

## 模型概述

Llama 3 70B 与 Llama 3 8B 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Meta / Meta | 2024-04-18 / 2024-04-18 | 8K / 8K | Llama 3 Community License / Llama 3 Community License |

## 基准测试表现

| 基准 | Llama 3 70B | Llama 3 8B | 胜出 |
|------|------|------|--------|
| ARC | 93.4 | 91.2 | A |
| BBH (BIG-Bench Hard) | 77.6 | 65.0 | A |
| GPQA | 38.2 | 27.9 | A |
| GSM8K (Grade School Math 8K) | 76.2 | 56.6 | A |
| HumanEval | 73.0 | 65.0 | A |
| IFEval | 72.2 | 68.2 | A |
| MATH | 50.1 | 40.0 | A |
| MMLU (Massive Multitask Language Understanding) | 79.5 | 67.8 | A |
| MUSR | 51.2 | 46.1 | A |
| WinoGrande | 79.2 | 75.6 | A |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Llama 3 70B

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 8K 偏小。

### Llama 3 8B

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 8K 偏小。

## 编辑点评

Llama 3 70B 与 Llama 3 8B 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Llama 3 70B 文档地址](https://llama.meta.com/docs/)
- [Llama 3 8B 文档地址](https://llama.meta.com/docs/)
