---
title: "Yi 34B vs Yi 6B：基准对比"
description: "详细对比 Yi 34B 与 Yi 6B 的基准表现、定价、上下文窗口与合规性。"
date: 2023-11-05
lastmod: 2023-11-05
draft: false
weight: 10
comparison_id: "yi-34b-vs-yi-6b"
models: ["yi-34b", "yi-6b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "other"]
---

# Yi 34B 对比 Yi 6B

## 模型概述

Yi 34B 与 Yi 6B 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Other / Other | 2023-11-05 / 2023-11-05 | 4K / 4K | Apache 2.0 / Apache 2.0 |

## 基准测试表现

| 基准 | Yi 34B | Yi 6B | 胜出 |
|------|------|------|--------|
| ARC | 87.2 | 88.4 | B |
| BBH (BIG-Bench Hard) | 48.8 | 55.3 | B |
| GPQA | 20.6 | 26.3 | B |
| GSM8K (Grade School Math 8K) | 48.3 | 37.0 | A |
| HumanEval | 35.8 | 42.3 | B |
| IFEval | 48.2 | 54.9 | B |
| MATH | 20.5 | 29.9 | B |
| MMLU (Massive Multitask Language Understanding) | 55.5 | 68.0 | B |
| MUSR | 36.8 | 29.5 | A |
| WinoGrande | 71.5 | 72.2 | B |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Yi 34B

- ✅ 可靠的通用模型。
- ⚠️ MMLU 仅 55.5，知识推理偏弱。
- ⚠️ HumanEval 35.8，代码能力较弱。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 4K 偏小。

### Yi 6B

- ✅ 可靠的通用模型。
- ⚠️ HumanEval 42.3，代码能力较弱。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 4K 偏小。

## 编辑点评

Yi 34B 与 Yi 6B 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Yi 34B 文档地址](https://huggingface.co/models)
- [Yi 6B 文档地址](https://huggingface.co/models)
