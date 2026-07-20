---
title: "GLM-4 Plus vs Qwen2.5 72B：基准对比"
description: "详细对比 GLM-4 Plus 与 Qwen2.5 72B 的基准表现、定价、上下文窗口与合规性。"
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
comparison_id: "glm-4-plus-vs-qwen2-5-72b"
models: ["glm-4-plus", "qwen2-5-72b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "alibaba"]
---

# GLM-4 Plus 对比 Qwen2.5 72B

## 模型概述

GLM-4 Plus 与 Qwen2.5 72B 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Other / Alibaba | 2024-08-12 / 2024-09-19 | 131K / 131K | Proprietary / Qwen License |

## 基准测试表现

| 基准 | GLM-4 Plus | Qwen2.5 72B | 胜出 |
|------|------|------|--------|
| ARC | 94.5 | — | A |
| BBH (BIG-Bench Hard) | 83.6 | 82.4 | A |
| GPQA | 35.4 | — | A |
| GSM8K (Grade School Math 8K) | 81.8 | 88.4 | B |
| HumanEval | 72.7 | 86.6 | B |
| IFEval | 79.2 | — | A |
| MATH | 53.3 | 83.1 | B |
| MMLU (Massive Multitask Language Understanding) | 84.3 | 86.1 | B |
| MUSR | 51.3 | — | A |
| WinoGrande | 85.8 | — | A |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### GLM-4 Plus

- ✅ MMLU 得分 84.3，知识推理能力强。
- ✅ 支持文本、图像、音频多模态输入。
- ⚠️ 闭源专有模型，不支持自托管。

### Qwen2.5 72B

- ✅ MMLU 得分 86.1，知识推理能力强。
- ✅ HumanEval 86.6，代码生成能力出色。
- ✅ GSM8K 88.4，数学推理稳健。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

GLM-4 Plus 与 Qwen2.5 72B 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [GLM-4 Plus 文档地址](https://huggingface.co/models)
- [Qwen2.5 72B 文档地址](https://qwenlm.github.io/)
