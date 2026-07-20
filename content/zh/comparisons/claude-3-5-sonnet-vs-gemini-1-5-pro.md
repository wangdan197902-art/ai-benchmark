---
title: "Claude 3.5 Sonnet vs Gemini 1.5 Pro：基准对比"
description: "详细对比 Claude 3.5 Sonnet 与 Gemini 1.5 Pro 的基准表现、定价、上下文窗口与合规性。"
date: 2024-06-20
lastmod: 2024-06-20
draft: false
weight: 10
comparison_id: "claude-3-5-sonnet-vs-gemini-1-5-pro"
models: ["claude-3-5-sonnet", "gemini-1-5-pro"]
benchmarks: ["bbh", "gsm8k", "humaneval", "math", "mmlu"]
verdict: "See Editor's Take section."
tags: ["comparison", "anthropic", "google"]
---

# Claude 3.5 Sonnet 对比 Gemini 1.5 Pro

## 模型概述

Claude 3.5 Sonnet 与 Gemini 1.5 Pro 均为 AI 模型市场的重要选项。本页对比两者在基准、定价与合规性上的差异。

## 核心规格对比

| 厂商 | 发布日期 | 上下文窗口 | 许可证 |
|---------|-------------|----------------|---------|
| Anthropic / Google | 2024-06-20 / 2024-02-15 | 200K / 2000K | Proprietary / Proprietary |

## 基准测试表现

| 基准 | Claude 3.5 Sonnet | Gemini 1.5 Pro | 胜出 |
|------|------|------|--------|
| BBH (BIG-Bench Hard) | 84.5 | 84.0 | A |
| GSM8K (Grade School Math 8K) | 96.4 | 91.7 | A |
| HumanEval | 92.0 | 71.9 | A |
| MATH | 71.1 | 58.5 | A |
| MMLU (Massive Multitask Language Understanding) | 88.7 | 85.9 | A |

## 定价对比

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*每百万 token — A / B*

## 优势 & 劣势

### Claude 3.5 Sonnet

- ✅ MMLU 得分 88.7，知识推理能力强。
- ✅ HumanEval 92.0，代码生成能力出色。
- ✅ GSM8K 96.4，数学推理稳健。
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

### Gemini 1.5 Pro

- ✅ MMLU 得分 85.9，知识推理能力强。
- ✅ GSM8K 91.7，数学推理稳健。
- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 2000K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

## 编辑点评

Claude 3.5 Sonnet 与 Gemini 1.5 Pro 各有侧重。建议根据具体场景（代码、长文本、视觉等）选择，参考上方基准与定价表。

## 常见问题

### 哪个模型在代码任务上更优？
参考 HumanEval 基准得分表，得分更高者更适合代码任务。

### 哪个模型价格更低？
参考上方的定价对比表，输入/输出价格更低者更具成本优势。

### 上下文窗口哪个更长？
参考核心规格对比表，上下文窗口更大的模型适合长文档处理。

## 参考文献

- [Claude 3.5 Sonnet 文档地址](https://docs.anthropic.com/claude/docs)
- [Gemini 1.5 Pro 文档地址](https://ai.google.dev/gemini-api/docs)
