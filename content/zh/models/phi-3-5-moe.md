---
title: "Phi-3.5 MoE：完整基准性能指南"
description: "深入分析 Phi-3.5 MoE 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-08-16
lastmod: 2024-08-16
draft: false
weight: 10
model_id: "phi-3-5-moe"
vendor: "other"
version: "phi-3-5-moe"
tags: ["open-weights", "moe", "self-hostable"]
---

# Phi-3.5 MoE

## 模型概述

Microsoft Phi-3.5 MoE 42B 混合专家模型, 128K 上下文, 总参 42B/活跃 6.6B, 性能接近 70B 稠密模型。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-5-moe | 2024-08-16 | 128K | text | text | MIT |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.7 | % | 5-shot |
| HumanEval | 69.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.5 | % | 0-shot CoT |
| MATH | 38.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.4 | % | 3-shot CoT |
| GPQA | 40.2 | % | 0-shot |
| IFEval | 74.3 | % | prompt_strict |
| ARC | 91.9 | % | challenge |
| MUSR | 50.3 | % | 0-shot |
| WinoGrande | 78.3 | % | 0-shot |

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

- 通用对话与问答

## 参考文献

- [Phi-3.5 MoE 文档地址](https://huggingface.co/models)
- 发布日期: 2024-08-16
- 厂商: Other
