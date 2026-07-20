---
title: "o1 mini: Complete Benchmark Performance Guide"
description: "In-depth analysis of o1 mini performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-12
lastmod: 2024-09-12
draft: false
weight: 10
model_id: "o1-mini"
vendor: "openai"
version: "o1-mini"
tags: ["reasoning", "coding"]
---

# o1 mini

## Model Overview

OpenAI o1-mini 经济型推理模型, 针对编程与数学优化, 比 o1 便宜 80%, 适合 STEM 任务。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | o1-mini | 2024-09-12 | 128K | text | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.2 | % | 5-shot |
| HumanEval | 78.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 86.6 | % | 0-shot CoT |
| MATH | 44.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 77.2 | % | 3-shot CoT |
| GPQA | 40.8 | % | 0-shot |
| IFEval | 73.1 | % | prompt_strict |
| ARC | 93.7 | % | challenge |
| MUSR | 54.0 | % | 0-shot |
| WinoGrande | 78.3 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- GSM8K 86.6, robust math reasoning.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging

## References

- [o1 mini Documentation](https://platform.openai.com/docs/models)
- Release Date: 2024-09-12
- Vendor: Openai
