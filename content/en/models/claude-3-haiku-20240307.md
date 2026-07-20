---
title: "Claude 3 Haiku (2024-03-07): Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Haiku (2024-03-07) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-07
lastmod: 2024-03-07
draft: false
weight: 10
model_id: "claude-3-haiku-20240307"
vendor: "anthropic"
version: "3-haiku-20240307"
tags: ["realtime"]
---

# Claude 3 Haiku (2024-03-07)

## Model Overview

Anthropic Claude 3 Haiku 2024-03-07 快照版本, 200K 上下文, 最快响应速度的经济型模型。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-haiku-20240307 | 2024-03-07 | 200K | text, image | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.1 | % | 5-shot |
| HumanEval | 74.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.5 | % | 0-shot CoT |
| MATH | 44.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.2 | % | 3-shot CoT |
| GPQA | 39.6 | % | 0-shot |
| IFEval | 75.3 | % | prompt_strict |
| ARC | 91.6 | % | challenge |
| MUSR | 51.0 | % | 0-shot |
| WinoGrande | 79.5 | % | 0-shot |

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

- Code generation and debugging

## References

- [Claude 3 Haiku (2024-03-07) Documentation](https://docs.anthropic.com/claude/docs)
- Release Date: 2024-03-07
- Vendor: Anthropic
