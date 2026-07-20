---
title: "GPT-3.5 Turbo：完整基准性能指南"
description: "深入分析 GPT-3.5 Turbo 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-03-01
lastmod: 2023-03-01
draft: false
weight: 10
model_id: "gpt-3.5-turbo"
vendor: "openai"
version: "3.5-turbo"
tags: ["legacy", "realtime"]
---

# GPT-3.5 Turbo

## 模型概述

OpenAI GPT-3.5 Turbo 经济型模型, 16K 上下文, 速度快价格低, 适合对话与通用任务。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 3.5-turbo | 2023-03-01 | 16K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 61.1 | % | 5-shot |
| HumanEval | 51.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 34.3 | % | 0-shot CoT |
| MATH | 17.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.2 | % | 3-shot CoT |
| GPQA | 22.4 | % | 0-shot |
| IFEval | 57.4 | % | prompt_strict |
| ARC | 86.8 | % | challenge |
| MUSR | 29.2 | % | 0-shot |
| WinoGrande | 76.7 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [GPT-3.5 Turbo 文档地址](https://platform.openai.com/docs/models)
- 发布日期: 2023-03-01
- 厂商: Openai
