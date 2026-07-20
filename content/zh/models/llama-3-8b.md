---
title: "Llama 3 8B：完整基准性能指南"
description: "深入分析 Llama 3 8B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-04-18
lastmod: 2024-04-18
draft: false
weight: 10
model_id: "llama-3-8b"
vendor: "meta"
version: "3-8b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3 8B

## 模型概述

Meta Llama 3 8B 经济型开源模型, 8K 上下文, 8B 参数, 性能超越 Llama 2 13B, 适合本地部署。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3-8b | 2024-04-18 | 8K | text | text | Llama 3 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 67.8 | % | 5-shot |
| HumanEval | 65.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 56.6 | % | 0-shot CoT |
| MATH | 40.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.0 | % | 3-shot CoT |
| GPQA | 27.9 | % | 0-shot |
| IFEval | 68.2 | % | prompt_strict |
| ARC | 91.2 | % | challenge |
| MUSR | 46.1 | % | 0-shot |
| WinoGrande | 75.6 | % | 0-shot |

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

- 通用对话与问答

## 参考文献

- [Llama 3 8B 文档地址](https://llama.meta.com/docs/)
- 发布日期: 2024-04-18
- 厂商: Meta
