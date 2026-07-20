---
title: "Qwen1.5 72B vs Qwen2 72B：基准对比"
description: "详细对比 Qwen1.5 72B 与 Qwen2 72B 的基准表现、定价、上下文窗口与合规性。"
date: 2024-02-25
lastmod: 2024-02-25
draft: false
weight: 10
comparison_id: "qwen1-5-72b-vs-qwen2-72b"
models: ["qwen1-5-72b", "qwen2-72b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "alibaba", "alibaba"]
---

# Qwen1.5 72B 对比 Qwen2 72B

## 模型概述

Qwen1.5 72B 与 Qwen2 72B 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Alibaba / Alibaba | 2024-02-25 / 2024-06-07 | 32K / 131K | Qwen License / Qwen License |

## 基准测试表现

| 基准 | Qwen1.5 72B | Qwen2 72B | 胜出 |
|------|------|------|--------|
| ARC | 92.6 | 94.4 | B |
| BBH (BIG-Bench Hard) | 76.5 | 83.4 | B |
| GPQA | 39.8 | 53.6 | B |
| GSM8K (Grade School Math 8K) | 80.9 | 87.0 | B |
| HumanEval | 65.2 | 76.5 | B |
| IFEval | 76.4 | 76.9 | B |
| MATH | 37.6 | 71.9 | B |
| MMLU (Massive Multitask Language Understanding) | 81.3 | 80.2 | A |
| MUSR | 50.8 | 68.9 | B |
| WinoGrande | 83.1 | 82.5 | A |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Qwen1.5 72B

- ✅ MMLU 得分 81.3，知识推理能力强。
- ⚠️ 闭源专有模型，不支持自托管。

### Qwen2 72B

- ✅ MMLU 得分 80.2，知识推理能力强。
- ✅ GSM8K 87.0，数学推理稳健。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

Qwen1.5 72B 与 Qwen2 72B 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Qwen1.5 72B 文档地址](https://qwenlm.github.io/)
- [Qwen2 72B 文档地址](https://qwenlm.github.io/)
