---
title: "OpenChat 3.6 8B：完整基准性能指南"
description: "深入分析 OpenChat 3.6 8B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-05-21
lastmod: 2024-05-21
draft: false
weight: 10
model_id: "openchat-3-6-8b"
vendor: "other"
version: "openchat-3-6-8b"
tags: ["open-weights", "self-hostable"]
---

# OpenChat 3.6 8B

## 模型概述

OpenChat 3.6 8B 对话模型, 8K 上下文, 基于 Llama 3 8B 微调, 改进推理与编码能力。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | openchat-3-6-8b | 2024-05-21 | 8K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.2 | % | 5-shot |
| HumanEval | 61.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.8 | % | 0-shot CoT |
| MATH | 33.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.0 | % | 3-shot CoT |
| GPQA | 30.3 | % | 0-shot |
| IFEval | 56.7 | % | prompt_strict |
| ARC | 89.2 | % | challenge |
| MUSR | 38.2 | % | 0-shot |
| WinoGrande | 74.5 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [OpenChat 3.6 8B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-05-21
- 厂商: Other
