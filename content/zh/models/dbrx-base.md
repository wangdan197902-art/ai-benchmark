---
title: "DBRX Base：完整基准性能指南"
description: "深入分析 DBRX Base 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-03-27
lastmod: 2024-03-27
draft: false
weight: 10
model_id: "dbrx-base"
vendor: "other"
version: "dbrx-base"
tags: ["open-weights", "moe", "self-hostable"]
---

# DBRX Base

## 模型概述

Databricks DBRX Base 基础 MoE 模型, 32K 上下文, 总参 132B/活跃 36B, 适合企业定制微调。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | dbrx-base | 2024-03-27 | 32K | text | text | DBRX Open Model License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.9 | % | 5-shot |
| HumanEval | 72.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.4 | % | 0-shot CoT |
| MATH | 36.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.3 | % | 3-shot CoT |
| GPQA | 39.3 | % | 0-shot |
| IFEval | 79.3 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 53.8 | % | 0-shot |
| WinoGrande | 79.8 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 采用 MoE 混合专家架构。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试

## 参考文献

- [DBRX Base 文档地址](https://huggingface.co/models)
- 发布日期: 2024-03-27
- 厂商: Other
