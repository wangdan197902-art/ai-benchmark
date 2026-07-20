---
title: "Text Bison：完整基准性能指南"
description: "深入分析 Text Bison 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-05-10
lastmod: 2023-05-10
draft: false
weight: 10
model_id: "text-bison"
vendor: "google"
version: "text-bison"
tags: ["legacy"]
---

# Text Bison

## 模型概述

Google Vertex AI Text Bison 文本生成模型, 基于 PaLM 2, 8K 上下文, 适合指令跟随与生成任务。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | text-bison | 2023-05-10 | 8K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 53.9 | % | 5-shot |
| HumanEval | 45.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 42.8 | % | 0-shot CoT |
| MATH | 12.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.2 | % | 3-shot CoT |
| GPQA | 27.7 | % | 0-shot |
| IFEval | 59.5 | % | prompt_strict |
| ARC | 86.7 | % | challenge |
| MUSR | 40.8 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 53.9，知识推理偏弱。
- HumanEval 45.1，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Text Bison 文档地址](https://ai.google.dev/gemini-api/docs)
- 发布日期: 2023-05-10
- 厂商: Google
