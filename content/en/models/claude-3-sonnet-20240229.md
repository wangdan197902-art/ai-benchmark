---
title: "Claude 3 Sonnet (2024-02-29): Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Sonnet (2024-02-29) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-29
lastmod: 2024-02-29
draft: false
weight: 10
model_id: "claude-3-sonnet-20240229"
vendor: "anthropic"
version: "3-sonnet-20240229"
tags: ["multimodal", "long-context"]
---

# Claude 3 Sonnet (2024-02-29)

## Model Overview

Anthropic Claude 3 Sonnet 2024-02-29 快照版本, 200K 上下文, 速度与智能平衡型。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-sonnet-20240229 | 2024-02-29 | 200K | text, image | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.0 | % | 5-shot |
| HumanEval | 80.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.6 | % | 0-shot CoT |
| MATH | 46.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.2 | % | 3-shot CoT |
| GPQA | 41.7 | % | 0-shot |
| IFEval | 75.5 | % | prompt_strict |
| ARC | 94.8 | % | challenge |
| MUSR | 63.5 | % | 0-shot |
| WinoGrande | 80.3 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- MMLU score 84.0, strong knowledge reasoning.
- HumanEval 80.1, excellent code generation.
- Input Modalities: text, image, audio.
- Context window 200K.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Long document summarization
- Vision and image understanding

## References

- [Claude 3 Sonnet (2024-02-29) Documentation](https://docs.anthropic.com/claude/docs)
- Release Date: 2024-02-29
- Vendor: Anthropic
