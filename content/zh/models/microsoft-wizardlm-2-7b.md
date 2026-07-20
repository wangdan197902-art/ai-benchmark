---
title: "Microsoft WizardLM 2 7B：完整基准性能指南"
description: "深入分析 Microsoft WizardLM 2 7B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-04-15
lastmod: 2024-04-15
draft: false
weight: 10
model_id: "microsoft-wizardlm-2-7b"
vendor: "other"
version: "wizardlm-2-7b"
tags: ["open-weights", "self-hostable"]
---

# Microsoft WizardLM 2 7B

## 模型概述

Microsoft WizardLM 2 7B 经济型微调模型, 32K 上下文, 基于 Llama 3 7B, 改进指令遵循能力。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardlm-2-7b | 2024-04-15 | 32K | text | text | Llama 3 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.7 | % | 5-shot |
| HumanEval | 68.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 58.5 | % | 0-shot CoT |
| MATH | 30.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 69.4 | % | 3-shot CoT |
| GPQA | 26.1 | % | 0-shot |
| IFEval | 56.9 | % | prompt_strict |
| ARC | 85.6 | % | challenge |
| MUSR | 49.3 | % | 0-shot |
| WinoGrande | 76.8 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 通用对话与问答

## 参考文献

- [Microsoft WizardLM 2 7B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-04-15
- 厂商: Other
