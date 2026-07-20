---
title: "DeepSeek V2 vs DeepSeek V3：基准对比"
description: "详细对比 DeepSeek V2 与 DeepSeek V3 的基准表现、定价、上下文窗口与合规性。"
date: 2024-05-07
lastmod: 2024-05-07
draft: false
weight: 10
comparison_id: "deepseek-v2-vs-deepseek-v3"
models: ["deepseek-v2", "deepseek-v3"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "deepseek", "deepseek"]
---

# DeepSeek V2 对比 DeepSeek V3

## 模型概述

DeepSeek V2 与 DeepSeek V3 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Deepseek / Deepseek | 2024-05-07 / 2024-12-26 | 32K / 64K | DeepSeek License / DeepSeek License |

## 基准测试表现

| 基准 | DeepSeek V2 | DeepSeek V3 | 胜出 |
|------|------|------|--------|
| ARC | 92.1 | — | A |
| BBH (BIG-Bench Hard) | 70.5 | 84.9 | B |
| GPQA | 31.5 | — | A |
| GSM8K (Grade School Math 8K) | 78.8 | 89.3 | B |
| HumanEval | 75.7 | 82.6 | B |
| IFEval | 78.6 | — | A |
| MATH | 35.2 | 61.6 | B |
| MMLU (Massive Multitask Language Understanding) | 78.2 | 88.5 | B |
| MUSR | 53.4 | — | A |
| WinoGrande | 84.7 | — | A |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### DeepSeek V2

- ✅ 采用 MoE 混合专家架构。
- ⚠️ 闭源专有模型，不支持自托管。

### DeepSeek V3

- ✅ MMLU 得分 88.5，知识推理能力强。
- ✅ HumanEval 82.6，代码生成能力出色。
- ✅ GSM8K 89.3，数学推理稳健。
- ✅ 采用 MoE 混合专家架构。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

DeepSeek V2 与 DeepSeek V3 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [DeepSeek V2 文档地址](https://api-docs.deepseek.com/)
- [DeepSeek V3 文档地址](https://api-docs.deepseek.com/)
