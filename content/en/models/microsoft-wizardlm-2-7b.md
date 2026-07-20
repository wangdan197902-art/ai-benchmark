---
title: "Microsoft WizardLM 2 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Microsoft WizardLM 2 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
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

## Model Overview

Microsoft WizardLM 2 7B 经济型微调模型, 32K 上下文, 基于 Llama 3 7B, 改进指令遵循能力。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardlm-2-7b | 2024-04-15 | 32K | text | text | Llama 3 Community License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
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

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- General chat and Q&A

## References

- [Microsoft WizardLM 2 7B Documentation](https://huggingface.co/models)
- Release Date: 2024-04-15
- Vendor: Other
