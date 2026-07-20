---
title: "WizardLM Team WizardLM 2 8x22B：完整基准性能指南"
description: "深入分析 WizardLM Team WizardLM 2 8x22B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-04-15
lastmod: 2024-04-15
draft: false
weight: 10
model_id: "wizardlmteam-wizardlm-2-8x22b"
vendor: "other"
version: "wizardlmteam-wizardlm-2-8x22b"
tags: ["open-weights", "moe", "self-hostable"]
---

# WizardLM Team WizardLM 2 8x22B

## 模型概述

WizardLM Team WizardLM 2 8x22B 官方发布版, 64K 上下文, 基于 Mixtral 8x22B 微调, Arena 上接近 GPT-4。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardlmteam-wizardlm-2-8x22b | 2024-04-15 | 65K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.2 | % | 5-shot |
| HumanEval | 70.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.9 | % | 0-shot CoT |
| MATH | 37.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 80.0 | % | 3-shot CoT |
| GPQA | 41.4 | % | 0-shot |
| IFEval | 70.7 | % | prompt_strict |
| ARC | 92.3 | % | challenge |
| MUSR | 56.8 | % | 0-shot |
| WinoGrande | 83.5 | % | 0-shot |

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

- [WizardLM Team WizardLM 2 8x22B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-04-15
- 厂商: Other
