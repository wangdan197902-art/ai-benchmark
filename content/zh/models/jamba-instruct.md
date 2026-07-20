---
title: "Jamba Instruct：完整基准性能指南"
description: "深入分析 Jamba Instruct 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-03-28
lastmod: 2024-03-28
draft: false
weight: 10
model_id: "jamba-instruct"
vendor: "other"
version: "jamba-instruct"
tags: ["open-weights", "long-context"]
---

# Jamba Instruct

## 模型概述

AI21 Labs Jamba Instruct 指令微调模型, 256K 上下文, 首个商用 Mamba-Transformer 混合架构。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | jamba-instruct | 2024-03-28 | 256K | text | text | Jamba Open Model License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.2 | % | 5-shot |
| HumanEval | 66.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.2 | % | 0-shot CoT |
| MATH | 49.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.8 | % | 3-shot CoT |
| GPQA | 37.4 | % | 0-shot |
| IFEval | 79.2 | % | prompt_strict |
| ARC | 91.2 | % | challenge |
| MUSR | 56.9 | % | 0-shot |
| WinoGrande | 78.3 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 上下文窗口 256K，支持长文本。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 长文档摘要

## 参考文献

- [Jamba Instruct 文档地址](https://huggingface.co/models)
- 发布日期: 2024-03-28
- 厂商: Other
