---
title: "Zephyr ORPO 141B Alpha：完整基准性能指南"
description: "深入分析 Zephyr ORPO 141B Alpha 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-03-22
lastmod: 2024-03-22
draft: false
weight: 10
model_id: "zephyr-orpo-141b-alpha"
vendor: "other"
version: "zephyr-orpo-141b-alpha"
tags: ["open-weights", "moe", "self-hostable"]
---

# Zephyr ORPO 141B Alpha

## 模型概述

HuggingFaceH4 Zephyr ORPO 141B Alpha, 4K 上下文, 基于 Mixtral 8x22B ORPO 微调, 性能接近 GPT-4。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | zephyr-orpo-141b-alpha | 2024-03-22 | 4K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.5 | % | 5-shot |
| HumanEval | 74.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 80.6 | % | 0-shot CoT |
| MATH | 36.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.3 | % | 3-shot CoT |
| GPQA | 36.8 | % | 0-shot |
| IFEval | 69.7 | % | prompt_strict |
| ARC | 91.4 | % | challenge |
| MUSR | 57.7 | % | 0-shot |
| WinoGrande | 79.7 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 采用 MoE 混合专家架构。

## 劣势

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 适用场景

- 代码生成与调试

## 参考文献

- [Zephyr ORPO 141B Alpha 文档地址](https://huggingface.co/models)
- 发布日期: 2024-03-22
- 厂商: Other
