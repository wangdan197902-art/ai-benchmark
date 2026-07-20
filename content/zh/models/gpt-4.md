---
title: "GPT-4：完整基准性能指南"
description: "深入分析 GPT-4 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-03-14
lastmod: 2023-03-14
draft: false
weight: 10
model_id: "gpt-4"
vendor: "openai"
version: "4"
tags: ["flagship", "reasoning"]
---

# GPT-4

## 模型概述

OpenAI GPT-4 大型语言模型, 8K 上下文, 在推理/创意/协作任务上显著超越 GPT-3.5, 首次引入人类水平表现。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4 | 2023-03-14 | 8K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 85.8 | % | 5-shot |
| HumanEval | 77.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 91.7 | % | 0-shot CoT |
| MATH | 43.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 80.9 | % | 3-shot CoT |
| GPQA | 39.2 | % | 0-shot |
| IFEval | 74.6 | % | prompt_strict |
| ARC | 94.1 | % | challenge |
| MUSR | 54.6 | % | 0-shot |
| WinoGrande | 80.3 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 85.8，知识推理能力强。
- GSM8K 91.7，数学推理稳健。

## 劣势

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## 适用场景

- 代码生成与调试
- Agent 工作流与工具调用

## 参考文献

- [GPT-4 文档地址](https://platform.openai.com/docs/models)
- 发布日期: 2023-03-14
- 厂商: Openai
