---
title: "GPT-3.5：完整基准性能指南"
description: "深入分析 GPT-3.5 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2022-11-30
lastmod: 2022-11-30
draft: false
weight: 10
model_id: "gpt-3.5"
vendor: "openai"
version: "3.5"
tags: ["legacy"]
---

# GPT-3.5

## 模型概述

OpenAI GPT-3.5 基础模型, 4K 上下文, ChatGPT 初始版本所用模型, 推理能力优于 GPT-3。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 3.5 | 2022-11-30 | 4K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 50.3 | % | 5-shot |
| HumanEval | 28.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 56.6 | % | 0-shot CoT |
| MATH | 29.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 63.9 | % | 3-shot CoT |
| GPQA | 26.9 | % | 0-shot |
| IFEval | 52.8 | % | prompt_strict |
| ARC | 81.8 | % | challenge |
| MUSR | 40.4 | % | 0-shot |
| WinoGrande | 72.7 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 50.3，知识推理偏弱。
- HumanEval 28.2，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [GPT-3.5 文档地址](https://platform.openai.com/docs/models)
- 发布日期: 2022-11-30
- 厂商: Openai
