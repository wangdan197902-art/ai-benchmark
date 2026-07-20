---
title: "GPT-4 32K：完整基准性能指南"
description: "深入分析 GPT-4 32K 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-03-14
lastmod: 2023-03-14
draft: false
weight: 10
model_id: "gpt-4-32k"
vendor: "openai"
version: "4-32k"
tags: ["flagship", "long-context", "reasoning"]
---

# GPT-4 32K

## 模型概述

OpenAI GPT-4 32K 上下文版本, 支持 32768 token 长文本输入, 适合长文档理解与生成任务。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-32k | 2023-03-14 | 32K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.8 | % | 5-shot |
| HumanEval | 76.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 81.6 | % | 0-shot CoT |
| MATH | 40.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.2 | % | 3-shot CoT |
| GPQA | 40.9 | % | 0-shot |
| IFEval | 74.7 | % | prompt_strict |
| ARC | 95.0 | % | challenge |
| MUSR | 54.9 | % | 0-shot |
| WinoGrande | 82.2 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 80.8，知识推理能力强。
- 上下文窗口 32K，支持长文本。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 长文档摘要
- Agent 工作流与工具调用

## 参考文献

- [GPT-4 32K 文档地址](https://platform.openai.com/docs/models)
- 发布日期: 2023-03-14
- 厂商: Openai
