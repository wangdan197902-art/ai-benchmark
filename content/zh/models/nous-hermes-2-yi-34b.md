---
title: "Nous Hermes 2 Yi 34B：完整基准性能指南"
description: "深入分析 Nous Hermes 2 Yi 34B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-01-22
lastmod: 2024-01-22
draft: false
weight: 10
model_id: "nous-hermes-2-yi-34b"
vendor: "other"
version: "nous-hermes-2-yi-34b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Nous Hermes 2 Yi 34B

## 模型概述

NousResearch Hermes 2 Yi 34B 微调模型, 4K 上下文, 基于 Yi 34B, 改进多语言与指令遵循。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-hermes-2-yi-34b | 2024-01-22 | 4K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.9 | % | 5-shot |
| HumanEval | 73.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.7 | % | 0-shot CoT |
| MATH | 44.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.6 | % | 3-shot CoT |
| GPQA | 39.0 | % | 0-shot |
| IFEval | 68.3 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 48.8 | % | 0-shot |
| WinoGrande | 83.4 | % | 0-shot |

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

- 代码生成与调试

## 参考文献

- [Nous Hermes 2 Yi 34B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-01-22
- 厂商: Other
