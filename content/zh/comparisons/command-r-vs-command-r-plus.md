---
title: "Command R vs Command R+：基准对比"
description: "详细对比 Command R 与 Command R+ 的基准表现、定价、上下文窗口与合规性。"
date: 2024-03-11
lastmod: 2024-03-11
draft: false
weight: 10
comparison_id: "command-r-vs-command-r-plus"
models: ["command-r", "command-r-plus"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "cohere", "cohere"]
---

# Command R 对比 Command R+

## 模型概述

Command R 与 Command R+ 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Cohere / Cohere | 2024-03-11 / 2024-04-04 | 128K / 128K | CC-BY-NC-4.0 / CC-BY-NC-4.0 |

## 基准测试表现

| 基准 | Command R | Command R+ | 胜出 |
|------|------|------|--------|
| ARC | 93.9 | — | A |
| BBH (BIG-Bench Hard) | 78.4 | 66.1 | A |
| GPQA | 44.0 | — | A |
| GSM8K (Grade School Math 8K) | 86.9 | 68.4 | A |
| HumanEval | 75.8 | 70.7 | A |
| IFEval | 74.1 | — | A |
| MATH | 43.9 | 35.6 | A |
| MMLU (Massive Multitask Language Understanding) | 79.3 | 75.0 | A |
| MUSR | 57.0 | — | A |
| WinoGrande | 84.8 | — | A |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Command R

- ✅ GSM8K 86.9，数学推理稳健。
- ✅ 企业级合规认证。
- ⚠️ 闭源专有模型，不支持自托管。

### Command R+

- ✅ 企业级合规认证。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

Command R 与 Command R+ 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Command R 文档地址](https://docs.cohere.com/docs)
- [Command R+ 文档地址](https://docs.cohere.com/docs/command-r-plus)
