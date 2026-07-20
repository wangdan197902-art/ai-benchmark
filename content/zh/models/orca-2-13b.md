---
title: "Orca 2 13B：完整基准性能指南"
description: "深入分析 Orca 2 13B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-11-20
lastmod: 2023-11-20
draft: false
weight: 10
model_id: "orca-2-13b"
vendor: "other"
version: "orca-2-13b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Orca 2 13B

## 模型概述

Microsoft Orca 2 13B 推理增强模型, 4K 上下文, 基于 Llama 2 微调, 通过渐进式复杂任务训练提升推理。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | orca-2-13b | 2023-11-20 | 4K | text | text | MIT |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.4 | % | 5-shot |
| HumanEval | 74.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.1 | % | 0-shot CoT |
| MATH | 42.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.8 | % | 3-shot CoT |
| GPQA | 42.5 | % | 0-shot |
| IFEval | 74.2 | % | prompt_strict |
| ARC | 91.4 | % | challenge |
| MUSR | 59.8 | % | 0-shot |
| WinoGrande | 80.2 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 适用场景

- 代码生成与调试

## 参考文献

- [Orca 2 13B 文档地址](https://huggingface.co/models)
- 发布日期: 2023-11-20
- 厂商: Other
