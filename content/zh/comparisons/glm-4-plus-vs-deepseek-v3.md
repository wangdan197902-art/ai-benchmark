---
title: "GLM-4 Plus vs DeepSeek V3：基准对比"
description: "详细对比 GLM-4 Plus 与 DeepSeek V3 的基准表现、定价、上下文窗口与合规性。"
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
comparison_id: "glm-4-plus-vs-deepseek-v3"
models: ["glm-4-plus", "deepseek-v3"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "deepseek"]
---

# GLM-4 Plus 对比 DeepSeek V3

## 模型概述

GLM-4 Plus 与 DeepSeek V3 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Other / Deepseek | 2024-08-12 / 2024-12-26 | 131K / 64K | Proprietary / DeepSeek License |

## 基准测试表现

| 基准 | GLM-4 Plus | DeepSeek V3 | 胜出 |
|------|------|------|--------|
| ARC | 94.5 | — | A |
| BBH (BIG-Bench Hard) | 83.6 | 84.9 | B |
| GPQA | 35.4 | — | A |
| GSM8K (Grade School Math 8K) | 81.8 | 89.3 | B |
| HumanEval | 72.7 | 82.6 | B |
| IFEval | 79.2 | — | A |
| MATH | 53.3 | 61.6 | B |
| MMLU (Massive Multitask Language Understanding) | 84.3 | 88.5 | B |
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

### DeepSeek V3

- ✅ MMLU 得分 88.5，知识推理能力强。
- ✅ HumanEval 82.6，代码生成能力出色。
- ✅ GSM8K 89.3，数学推理稳健。
- ✅ 采用 MoE 混合专家架构。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

GLM-4 Plus 与 DeepSeek V3 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [GLM-4 Plus 文档地址](https://huggingface.co/models)
- [DeepSeek V3 文档地址](https://api-docs.deepseek.com/)
