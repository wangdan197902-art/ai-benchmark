---
title: "Claude 3.5 Sonnet (2024-10-22): Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3.5 Sonnet (2024-10-22) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-22
lastmod: 2024-10-22
draft: false
weight: 10
model_id: "claude-3-5-sonnet-20241022"
vendor: "anthropic"
version: "3.5-sonnet-20241022"
tags: ["flagship", "coding", "long-context"]
---

# Claude 3.5 Sonnet (2024-10-22)

## Model Overview

Anthropic Claude 3.5 Sonnet 2024-10-22 版本, 引入计算机使用能力, 编码与推理性能再次提升。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3.5-sonnet-20241022 | 2024-10-22 | 200K | text, image | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 87.2 | % | 5-shot |
| HumanEval | 86.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 94.0 | % | 0-shot CoT |
| MATH | 75.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 84.2 | % | 3-shot CoT |
| GPQA | 50.9 | % | 0-shot |
| IFEval | 81.6 | % | prompt_strict |
| ARC | 96.8 | % | challenge |
| MUSR | 71.8 | % | 0-shot |
| WinoGrande | 86.9 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- MMLU score 87.2, strong knowledge reasoning.
- HumanEval 86.1, excellent code generation.
- GSM8K 94.0, robust math reasoning.
- Context window 200K.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Long document summarization
- Agent workflows and tool use

## References

- [Claude 3.5 Sonnet (2024-10-22) Documentation](https://docs.anthropic.com/claude/docs)
- Release Date: 2024-10-22
- Vendor: Anthropic
