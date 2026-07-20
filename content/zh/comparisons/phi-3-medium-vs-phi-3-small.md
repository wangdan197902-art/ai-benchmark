---
title: "Phi-3 Medium vs Phi-3 Small：基准对比"
description: "详细对比 Phi-3 Medium 与 Phi-3 Small 的基准表现、定价、上下文窗口与合规性。"
date: 2024-05-21
lastmod: 2024-05-21
draft: false
weight: 10
comparison_id: "phi-3-medium-vs-phi-3-small"
models: ["phi-3-medium", "phi-3-small"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "other"]
---

# Phi-3 Medium 对比 Phi-3 Small

## 模型概述

Phi-3 Medium 与 Phi-3 Small 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Other / Other | 2024-05-21 / 2024-05-21 | 4K / 8K | MIT / MIT |

## 基准测试表现

| 基准 | Phi-3 Medium | Phi-3 Small | 胜出 |
|------|------|------|--------|
| ARC | 90.1 | 89.6 | A |
| BBH (BIG-Bench Hard) | 71.4 | 71.8 | Tie |
| GPQA | 25.6 | 30.9 | B |
| GSM8K (Grade School Math 8K) | 59.0 | 62.7 | B |
| HumanEval | 53.9 | 68.3 | B |
| IFEval | 67.4 | 61.0 | A |
| MATH | 34.3 | 43.5 | B |
| MMLU (Massive Multitask Language Understanding) | 62.1 | 71.8 | B |
| MUSR | 43.9 | 36.5 | A |
| WinoGrande | 72.1 | 74.9 | B |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Phi-3 Medium

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 4K 偏小。

### Phi-3 Small

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 8K 偏小。

## 编辑点评

Phi-3 Medium 与 Phi-3 Small 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Phi-3 Medium 文档地址](https://huggingface.co/models)
- [Phi-3 Small 文档地址](https://huggingface.co/models)
