---
title: "GPT-3.5 Turbo: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-3.5 Turbo performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-03-01
lastmod: 2023-03-01
draft: false
weight: 10
model_id: "gpt-3.5-turbo"
vendor: "openai"
version: "3.5-turbo"
tags: ["legacy", "realtime"]
---

# GPT-3.5 Turbo

## Model Overview

OpenAI GPT-3.5 Turbo 经济型模型, 16K 上下文, 速度快价格低, 适合对话与通用任务。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 3.5-turbo | 2023-03-01 | 16K | text | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 61.1 | % | 5-shot |
| HumanEval | 51.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 34.3 | % | 0-shot CoT |
| MATH | 17.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.2 | % | 3-shot CoT |
| GPQA | 22.4 | % | 0-shot |
| IFEval | 57.4 | % | prompt_strict |
| ARC | 86.8 | % | challenge |
| MUSR | 29.2 | % | 0-shot |
| WinoGrande | 76.7 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- Proprietary, not self-hostable.
- Context window 16K is limited.

## Use Cases

- General chat and Q&A

## References

- [GPT-3.5 Turbo Documentation](https://platform.openai.com/docs/models)
- Release Date: 2023-03-01
- Vendor: Openai
