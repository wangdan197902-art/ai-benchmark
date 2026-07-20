---
title: "Code Llama 70B：完整基准性能指南"
description: "深入分析 Code Llama 70B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-01-29
lastmod: 2024-01-29
draft: false
weight: 10
model_id: "code-llama-70b"
vendor: "meta"
version: "code-llama-70b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Code Llama 70B

## 模型概述

Meta Code Llama 70B 代码专用开源模型, 16K 上下文, 基于 Llama 2 微调, 支持多语言代码生成。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | code-llama-70b | 2024-01-29 | 16K | text | text | Llama 2 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 62.1 | % | 5-shot |
| HumanEval | 65.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 61.0 | % | 0-shot CoT |
| MATH | 34.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.1 | % | 3-shot CoT |
| GPQA | 25.3 | % | 0-shot |
| IFEval | 63.8 | % | prompt_strict |
| ARC | 89.8 | % | challenge |
| MUSR | 40.1 | % | 0-shot |
| WinoGrande | 75.5 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## 适用场景

- 代码生成与调试

## 参考文献

- [Code Llama 70B 文档地址](https://llama.meta.com/docs/)
- 发布日期: 2024-01-29
- 厂商: Meta
