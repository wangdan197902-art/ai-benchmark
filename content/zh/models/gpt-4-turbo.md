---
title: "GPT-4 Turbo：完整基准性能指南"
description: "深入分析 GPT-4 Turbo 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-11-06
lastmod: 2023-11-06
draft: false
weight: 10
model_id: "gpt-4-turbo"
vendor: "openai"
version: "turbo"
tags: ["flagship", "multimodal", "long-context"]
---

# GPT-4 Turbo

## 模型概述

OpenAI GPT-4 Turbo 模型, 128K 上下文窗口, 支持视觉输入, 相比 GPT-4 价格降低 3 倍, 性能提升。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | turbo | 2023-11-06 | 128K | text, image | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.4 | % | 5-shot |
| HumanEval | 80.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 85.2 | % | 0-shot CoT |
| MATH | 50.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.5 | % | 3-shot CoT |
| GPQA | 49.2 | % | 0-shot |
| IFEval | 77.9 | % | prompt_strict |
| ARC | 94.2 | % | challenge |
| MUSR | 61.1 | % | 0-shot |
| WinoGrande | 80.8 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 84.4，知识推理能力强。
- HumanEval 80.5，代码生成能力出色。
- GSM8K 85.2，数学推理稳健。
- 支持文本、图像、音频多模态输入。
- 上下文窗口 128K，支持长文本。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 长文档摘要
- 视觉与图像理解
- Agent 工作流与工具调用

## 参考文献

- [GPT-4 Turbo 文档地址](https://platform.openai.com/docs/models)
- 发布日期: 2023-11-06
- 厂商: Openai
