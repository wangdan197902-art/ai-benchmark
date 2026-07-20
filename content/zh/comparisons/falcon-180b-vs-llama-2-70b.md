---
title: "Falcon 180B vs Llama 2 70B：基准对比"
description: "详细对比 Falcon 180B 与 Llama 2 70B 的基准表现、定价、上下文窗口与合规性。"
date: 2023-09-06
lastmod: 2023-09-06
draft: false
weight: 10
comparison_id: "falcon-180b-vs-llama-2-70b"
models: ["falcon-180b", "llama-2-70b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "meta"]
---

# Falcon 180B 对比 Llama 2 70B

## 模型概述

Falcon 180B 与 Llama 2 70B 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Other / Meta | 2023-09-06 / 2023-07-18 | 2K / 4K | TII Falcon LLM License / Llama 2 Community License |

## 基准测试表现

| 基准 | Falcon 180B | Llama 2 70B | 胜出 |
|------|------|------|--------|
| ARC | 91.6 | 80.3 | A |
| BBH (BIG-Bench Hard) | 76.4 | 62.5 | A |
| GPQA | 43.2 | 27.2 | A |
| GSM8K (Grade School Math 8K) | 77.5 | 51.8 | A |
| HumanEval | 68.9 | 50.6 | A |
| IFEval | 70.5 | 57.1 | A |
| MATH | 44.8 | 22.4 | A |
| MMLU (Massive Multitask Language Understanding) | 76.7 | 53.0 | A |
| MUSR | 59.1 | 36.1 | A |
| WinoGrande | 80.0 | 73.4 | A |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Falcon 180B

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 2K 偏小。

### Llama 2 70B

- ✅ 可靠的通用模型。
- ⚠️ MMLU 仅 53.0，知识推理偏弱。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 4K 偏小。

## 编辑点评

Falcon 180B 与 Llama 2 70B 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Falcon 180B 文档地址](https://huggingface.co/models)
- [Llama 2 70B 文档地址](https://llama.meta.com/docs/)
