---
title: "Ministral 8B：完整基准性能指南"
description: "深入分析 Ministral 8B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-10-16
lastmod: 2024-10-16
draft: false
weight: 10
model_id: "ministral-8b"
vendor: "mistral"
version: "ministral-8b"
tags: ["open-weights", "self-hostable", "long-context"]
---

# Ministral 8B

## 模型概述

Mistral Ministral 8B 边缘模型, 128K 上下文, 8B 参数, 为本地与边缘计算优化, 性能超越 Llama 3 8B。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | ministral-8b | 2024-10-16 | 128K | text | text | Mistral Research License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.9 | % | 5-shot |
| HumanEval | 63.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.7 | % | 0-shot CoT |
| MATH | 39.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.0 | % | 3-shot CoT |
| GPQA | 35.1 | % | 0-shot |
| IFEval | 56.1 | % | prompt_strict |
| ARC | 85.5 | % | challenge |
| MUSR | 37.0 | % | 0-shot |
| WinoGrande | 75.3 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 上下文窗口 128K，支持长文本。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 长文档摘要

## 参考文献

- [Ministral 8B 文档地址](https://docs.mistral.ai/)
- 发布日期: 2024-10-16
- 厂商: Mistral
