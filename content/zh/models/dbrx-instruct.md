---
title: "DBRX Instruct：完整基准性能指南"
description: "深入分析 DBRX Instruct 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-03-27
lastmod: 2024-03-27
draft: false
weight: 10
model_id: "dbrx-instruct"
vendor: "other"
version: "dbrx-instruct"
tags: ["open-weights", "moe", "self-hostable"]
---

# DBRX Instruct

## 模型概述

Databricks DBRX Instruct MoE 模型, 32K 上下文, 总参 132B/活跃 36B, 在开源模型中编程/数学领先。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | dbrx-instruct | 2024-03-27 | 32K | text | text | DBRX Open Model License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.3 | % | 5-shot |
| HumanEval | 72.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.7 | % | 0-shot CoT |
| MATH | 50.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.7 | % | 3-shot CoT |
| GPQA | 34.7 | % | 0-shot |
| IFEval | 73.1 | % | prompt_strict |
| ARC | 93.9 | % | challenge |
| MUSR | 54.7 | % | 0-shot |
| WinoGrande | 81.8 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 81.3，知识推理能力强。
- 采用 MoE 混合专家架构。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试

## 参考文献

- [DBRX Instruct 文档地址](https://huggingface.co/models)
- 发布日期: 2024-03-27
- 厂商: Other
