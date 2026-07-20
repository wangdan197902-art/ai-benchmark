---
title: "GPT-3.5: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-3.5 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2022-11-30
lastmod: 2022-11-30
draft: false
weight: 10
model_id: "gpt-3.5"
vendor: "openai"
version: "3.5"
tags: ["legacy"]
---

# GPT-3.5

## Model Overview

OpenAI GPT-3.5 基础模型, 4K 上下文, ChatGPT 初始版本所用模型, 推理能力优于 GPT-3。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 3.5 | 2022-11-30 | 4K | text | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 50.3 | % | 5-shot |
| HumanEval | 28.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 56.6 | % | 0-shot CoT |
| MATH | 29.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 63.9 | % | 3-shot CoT |
| GPQA | 26.9 | % | 0-shot |
| IFEval | 52.8 | % | prompt_strict |
| ARC | 81.8 | % | challenge |
| MUSR | 40.4 | % | 0-shot |
| WinoGrande | 72.7 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 50.3, weak knowledge reasoning.
- HumanEval 28.2, coding weak.
- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- General chat and Q&A

## References

- [GPT-3.5 Documentation](https://platform.openai.com/docs/models)
- Release Date: 2022-11-30
- Vendor: Openai
