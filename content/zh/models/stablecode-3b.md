---
title: "StableCode 3B：完整基准性能指南"
description: "深入分析 StableCode 3B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-01-19
lastmod: 2024-01-19
draft: false
weight: 10
model_id: "stablecode-3b"
vendor: "other"
version: "stablecode-3b"
tags: ["open-weights", "coding", "self-hostable", "long-context"]
---

# StableCode 3B

## 模型概述

Stability AI StableCode 3B 代码专用模型, 100K 上下文, 3B 参数, 支持多种编程语言代码补全。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | stablecode-3b | 2024-01-19 | 100K | text | text | Stability AI Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.4 | % | 5-shot |
| HumanEval | 77.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 68.5 | % | 0-shot CoT |
| MATH | 31.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 58.4 | % | 3-shot CoT |
| GPQA | 24.5 | % | 0-shot |
| IFEval | 51.8 | % | prompt_strict |
| ARC | 86.4 | % | challenge |
| MUSR | 51.8 | % | 0-shot |
| WinoGrande | 70.9 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 上下文窗口 100K，支持长文本。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 长文档摘要

## 参考文献

- [StableCode 3B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-01-19
- 厂商: Other
