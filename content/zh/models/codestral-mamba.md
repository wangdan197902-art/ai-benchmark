---
title: "Codestral Mamba：完整基准性能指南"
description: "深入分析 Codestral Mamba 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-07-16
lastmod: 2024-07-16
draft: false
weight: 10
model_id: "codestral-mamba"
vendor: "mistral"
version: "codestral-mamba"
tags: ["coding", "open-weights", "long-context"]
---

# Codestral Mamba

## 模型概述

Mistral Codestral Mamba 7B 代码模型, 256K 上下文, 基于 Mamba 架构, 线性时间复杂度适合长序列。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | codestral-mamba | 2024-07-16 | 256K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 59.3 | % | 5-shot |
| HumanEval | 86.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 67.8 | % | 0-shot CoT |
| MATH | 28.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.0 | % | 3-shot CoT |
| GPQA | 36.3 | % | 0-shot |
| IFEval | 65.5 | % | prompt_strict |
| ARC | 87.4 | % | challenge |
| MUSR | 47.0 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- HumanEval 86.2，代码生成能力出色。
- 上下文窗口 256K，支持长文本。

## 劣势

- MMLU 仅 59.3，知识推理偏弱。
- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 长文档摘要

## 参考文献

- [Codestral Mamba 文档地址](https://docs.mistral.ai/)
- 发布日期: 2024-07-16
- 厂商: Mistral
