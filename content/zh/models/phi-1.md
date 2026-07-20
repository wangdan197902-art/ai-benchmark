---
title: "Phi-1：完整基准性能指南"
description: "深入分析 Phi-1 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-09-14
lastmod: 2023-09-14
draft: false
weight: 10
model_id: "phi-1"
vendor: "other"
version: "phi-1"
tags: ["open-weights", "coding", "self-hostable", "legacy"]
---

# Phi-1

## 模型概述

Microsoft Phi-1 1.3B 代码模型, 2K 上下文, 专为代码生成训练, 在 1.3B 规模上 HumanEval 表现突出。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-1 | 2023-09-14 | 2K | text | text | MIT |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 68.1 | % | 5-shot |
| HumanEval | 88.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.6 | % | 0-shot CoT |
| MATH | 25.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 69.9 | % | 3-shot CoT |
| GPQA | 22.1 | % | 0-shot |
| IFEval | 53.8 | % | prompt_strict |
| ARC | 88.4 | % | challenge |
| MUSR | 49.0 | % | 0-shot |
| WinoGrande | 74.5 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- HumanEval 88.1，代码生成能力出色。

## 劣势

- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## 适用场景

- 代码生成与调试

## 参考文献

- [Phi-1 文档地址](https://huggingface.co/models)
- 发布日期: 2023-09-14
- 厂商: Other
