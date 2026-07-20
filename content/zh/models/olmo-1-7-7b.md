---
title: "OLMo 1.7 7B：完整基准性能指南"
description: "深入分析 OLMo 1.7 7B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-08-23
lastmod: 2024-08-23
draft: false
weight: 10
model_id: "olmo-1-7-7b"
vendor: "other"
version: "olmo-1-7-7b"
tags: ["open-weights", "self-hostable"]
---

# OLMo 1.7 7B

## 模型概述

AllenAI OLMo 1.7 7B 第二代模型, 4K 上下文, 改进训练流程, 性能超越初代 OLMo 7B。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | olmo-1-7-7b | 2024-08-23 | 4K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.5 | % | 5-shot |
| HumanEval | 67.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.5 | % | 0-shot CoT |
| MATH | 38.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 68.9 | % | 3-shot CoT |
| GPQA | 26.9 | % | 0-shot |
| IFEval | 61.2 | % | prompt_strict |
| ARC | 91.8 | % | challenge |
| MUSR | 42.6 | % | 0-shot |
| WinoGrande | 76.6 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [OLMo 1.7 7B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-08-23
- 厂商: Other
