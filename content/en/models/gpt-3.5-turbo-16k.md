---
title: "GPT-3.5 Turbo 16K: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-3.5 Turbo 16K performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-06-13
lastmod: 2023-06-13
draft: false
weight: 10
model_id: "gpt-3.5-turbo-16k"
vendor: "openai"
version: "3.5-turbo-16k"
tags: ["legacy", "long-context"]
---

# GPT-3.5 Turbo 16K

## Model Overview

OpenAI GPT-3.5 Turbo 16K 长上下文版本, 支持 16385 token, 适合中等长度文档处理。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 3.5-turbo-16k | 2023-06-13 | 16K | text | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.2 | % | 5-shot |
| HumanEval | 36.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 52.8 | % | 0-shot CoT |
| MATH | 30.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.2 | % | 3-shot CoT |
| GPQA | 21.6 | % | 0-shot |
| IFEval | 48.5 | % | prompt_strict |
| ARC | 83.1 | % | challenge |
| MUSR | 29.1 | % | 0-shot |
| WinoGrande | 74.0 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Context window 16K.

## Weaknesses

- HumanEval 36.8, coding weak.
- Proprietary, not self-hostable.
- Context window 16K is limited.

## Use Cases

- Long document summarization

## References

- [GPT-3.5 Turbo 16K Documentation](https://platform.openai.com/docs/models)
- Release Date: 2023-06-13
- Vendor: Openai
