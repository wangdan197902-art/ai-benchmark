---
title: "Yi Large vs Yi 34B：基准对比"
description: "详细对比 Yi Large 与 Yi 34B 的基准表现、定价、上下文窗口与合规性。"
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
comparison_id: "yi-large-vs-yi-34b"
models: ["yi-large", "yi-34b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "other"]
---

# Yi Large 对比 Yi 34B

## 模型概述

Yi Large 与 Yi 34B 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Other / Other | 2024-05-13 / 2023-11-05 | 32K / 4K | Proprietary / Apache 2.0 |

## 基准测试表现

| 基准 | Yi Large | Yi 34B | 胜出 |
|------|------|------|--------|
| ARC | 94.8 | 87.2 | A |
| BBH (BIG-Bench Hard) | 77.1 | 48.8 | A |
| GPQA | 35.2 | 20.6 | A |
| GSM8K (Grade School Math 8K) | 81.3 | 48.3 | A |
| HumanEval | 72.2 | 35.8 | A |
| IFEval | 73.4 | 48.2 | A |
| MATH | 55.9 | 20.5 | A |
| MMLU (Massive Multitask Language Understanding) | 82.8 | 55.5 | A |
| MUSR | 59.4 | 36.8 | A |
| WinoGrande | 84.1 | 71.5 | A |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Yi Large

- ✅ MMLU 得分 82.8，知识推理能力强。
- ⚠️ 闭源专有模型，不支持自托管。

### Yi 34B

- ✅ 可靠的通用模型。
- ⚠️ MMLU 仅 55.5，知识推理偏弱。
- ⚠️ HumanEval 35.8，代码能力较弱。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 4K 偏小。

## 编辑点评

Yi Large 与 Yi 34B 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Yi Large 文档地址](https://huggingface.co/models)
- [Yi 34B 文档地址](https://huggingface.co/models)
