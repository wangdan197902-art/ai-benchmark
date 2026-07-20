---
title: "Mistral Small 3：完整基准性能指南"
description: "深入分析 Mistral Small 3 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2025-01-29
lastmod: 2025-01-29
draft: false
weight: 10
model_id: "mistral-small-3"
vendor: "mistral"
version: "small-3"
tags: ["open-weights", "self-hostable"]
---

# Mistral Small 3

## 模型概述

Mistral Small 3 开源模型, 24B 参数, 32K 上下文, 性能接近 Mistral Large 2, Apache 2.0 可商用。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | small-3 | 2025-01-29 | 32K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.9 | % | 5-shot |
| HumanEval | 74.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.6 | % | 0-shot CoT |
| MATH | 39.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.3 | % | 3-shot CoT |
| GPQA | 30.1 | % | 0-shot |
| IFEval | 76.9 | % | prompt_strict |
| ARC | 91.8 | % | challenge |
| MUSR | 46.0 | % | 0-shot |
| WinoGrande | 78.8 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试

## 参考文献

- [Mistral Small 3 文档地址](https://docs.mistral.ai/)
- 发布日期: 2025-01-29
- 厂商: Mistral
