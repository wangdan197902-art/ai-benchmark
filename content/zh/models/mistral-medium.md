---
title: "Mistral Medium：完整基准性能指南"
description: "深入分析 Mistral Medium 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-12-11
lastmod: 2023-12-11
draft: false
weight: 10
model_id: "mistral-medium"
vendor: "mistral"
version: "medium"
tags: ["eu-residency"]
---

# Mistral Medium

## 模型概述

Mistral AI Medium 中端模型, 32K 上下文, 平衡性能与成本, 适合企业级通用任务。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | medium | 2023-12-11 | 32K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.9 | % | 5-shot |
| HumanEval | 78.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.5 | % | 0-shot CoT |
| MATH | 54.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.4 | % | 3-shot CoT |
| GPQA | 48.7 | % | 0-shot |
| IFEval | 77.4 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 64.3 | % | 0-shot |
| WinoGrande | 82.4 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 82.9，知识推理能力强。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试

## 参考文献

- [Mistral Medium 文档地址](https://docs.mistral.ai/)
- 发布日期: 2023-12-11
- 厂商: Mistral
