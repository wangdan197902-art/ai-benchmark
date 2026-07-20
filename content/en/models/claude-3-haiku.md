---
title: "Claude 3 Haiku: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Haiku performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-07
lastmod: 2024-03-07
draft: false
weight: 10
model_id: "claude-3-haiku"
vendor: "anthropic"
version: "3-haiku"
tags: ["realtime"]
---

# Claude 3 Haiku

## Model Overview

Anthropic Claude 3 Haiku 经济型模型, 200K 上下文, 响应速度最快, 适合高吞吐量实时场景。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-haiku | 2024-03-07 | 200K | text, image | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.9 | % | 5-shot |
| HumanEval | 69.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.2 | % | 0-shot CoT |
| MATH | 52.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.7 | % | 3-shot CoT |
| GPQA | 44.4 | % | 0-shot |
| IFEval | 70.8 | % | prompt_strict |
| ARC | 94.3 | % | challenge |
| MUSR | 58.1 | % | 0-shot |
| WinoGrande | 84.8 | % | 0-shot |

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

- [Claude 3 Haiku Documentation](https://docs.anthropic.com/claude/docs)
- Release Date: 2024-03-07
- Vendor: Anthropic
