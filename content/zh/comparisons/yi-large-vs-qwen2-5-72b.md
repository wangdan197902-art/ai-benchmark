---
title: "Yi Large vs Qwen2.5 72B：基准对比"
description: "详细对比 Yi Large 与 Qwen2.5 72B 的基准表现、定价、上下文窗口与合规性。"
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
comparison_id: "yi-large-vs-qwen2-5-72b"
models: ["yi-large", "qwen2-5-72b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "alibaba"]
---

# Yi Large 对比 Qwen2.5 72B

## 模型概述

Yi Large 与 Qwen2.5 72B 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Other / Alibaba | 2024-05-13 / 2024-09-19 | 32K / 131K | Proprietary / Qwen License |

## 基准测试表现

| 基准 | Yi Large | Qwen2.5 72B | 胜出 |
|------|------|------|--------|
| ARC | 94.8 | — | A |
| BBH (BIG-Bench Hard) | 77.1 | 82.4 | B |
| GPQA | 35.2 | — | A |
| GSM8K (Grade School Math 8K) | 81.3 | 88.4 | B |
| HumanEval | 72.2 | 86.6 | B |
| IFEval | 73.4 | — | A |
| MATH | 55.9 | 83.1 | B |
| MMLU (Massive Multitask Language Understanding) | 82.8 | 86.1 | B |
| MUSR | 59.4 | — | A |
| WinoGrande | 84.1 | — | A |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Yi Large

- ✅ MMLU 得分 82.8，知识推理能力强。
- ⚠️ 闭源专有模型，不支持自托管。

### Qwen2.5 72B

- ✅ MMLU 得分 86.1，知识推理能力强。
- ✅ HumanEval 86.6，代码生成能力出色。
- ✅ GSM8K 88.4，数学推理稳健。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

Yi Large 与 Qwen2.5 72B 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Yi Large 文档地址](https://huggingface.co/models)
- [Qwen2.5 72B 文档地址](https://qwenlm.github.io/)
