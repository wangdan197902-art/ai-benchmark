---
title: "Microsoft WizardLM 2 8x22B：完整基准性能指南"
description: "深入分析 Microsoft WizardLM 2 8x22B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-04-15
lastmod: 2024-04-15
draft: false
weight: 10
model_id: "microsoft-wizardlm-2-8x22b"
vendor: "other"
version: "wizardlm-2-8x22b"
tags: ["open-weights", "moe", "self-hostable"]
---

# Microsoft WizardLM 2 8x22B

## 模型概述

Microsoft WizardLM 2 8x22B 微调模型, 64K 上下文, 基于 Mixtral 8x22B, 在 Arena 上接近 GPT-4。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardlm-2-8x22b | 2024-04-15 | 65K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.9 | % | 5-shot |
| HumanEval | 77.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.7 | % | 0-shot CoT |
| MATH | 39.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 73.6 | % | 3-shot CoT |
| GPQA | 39.3 | % | 0-shot |
| IFEval | 75.3 | % | prompt_strict |
| ARC | 92.1 | % | challenge |
| MUSR | 58.0 | % | 0-shot |
| WinoGrande | 81.6 | % | 0-shot |

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

- [Microsoft WizardLM 2 8x22B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-04-15
- 厂商: Other
