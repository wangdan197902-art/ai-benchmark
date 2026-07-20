---
title: "Code Llama 34B：完整基准性能指南"
description: "深入分析 Code Llama 34B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-08-24
lastmod: 2023-08-24
draft: false
weight: 10
model_id: "code-llama-34b"
vendor: "meta"
version: "code-llama-34b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Code Llama 34B

## 模型概述

Meta Code Llama 34B 代码专用开源模型, 16K 上下文, 中等规模, 平衡代码生成性能与资源消耗。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | code-llama-34b | 2023-08-24 | 16K | text | text | Llama 2 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 74.5 | % | 5-shot |
| HumanEval | 71.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 59.8 | % | 0-shot CoT |
| MATH | 44.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 59.1 | % | 3-shot CoT |
| GPQA | 27.0 | % | 0-shot |
| IFEval | 58.7 | % | prompt_strict |
| ARC | 88.7 | % | challenge |
| MUSR | 44.9 | % | 0-shot |
| WinoGrande | 80.0 | % | 0-shot |

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

- [Code Llama 34B 文档地址](https://llama.meta.com/docs/)
- 发布日期: 2023-08-24
- 厂商: Meta
