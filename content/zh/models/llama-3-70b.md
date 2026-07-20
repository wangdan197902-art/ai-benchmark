---
title: "Llama 3 70B：完整基准性能指南"
description: "深入分析 Llama 3 70B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-04-18
lastmod: 2024-04-18
draft: false
weight: 10
model_id: "llama-3-70b"
vendor: "meta"
version: "3-70b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3 70B

## 模型概述

Meta Llama 3 70B 中端开源模型, 8K 上下文, 在 MMLU/HumanEval 上接近 GPT-4, 开源旗舰之一。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3-70b | 2024-04-18 | 8K | text | text | Llama 3 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.5 | % | 5-shot |
| HumanEval | 73.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 76.2 | % | 0-shot CoT |
| MATH | 50.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 77.6 | % | 3-shot CoT |
| GPQA | 38.2 | % | 0-shot |
| IFEval | 72.2 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 51.2 | % | 0-shot |
| WinoGrande | 79.2 | % | 0-shot |

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

- 代码生成与调试

## 参考文献

- [Llama 3 70B 文档地址](https://llama.meta.com/docs/)
- 发布日期: 2024-04-18
- 厂商: Meta
