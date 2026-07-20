---
title: "Claude 3 Opus (2024-02-29): Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Opus (2024-02-29) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-29
lastmod: 2024-02-29
draft: false
weight: 10
model_id: "claude-3-opus-20240229"
vendor: "anthropic"
version: "3-opus-20240229"
tags: ["flagship", "multimodal", "long-context"]
---

# Claude 3 Opus (2024-02-29)

## Model Overview

Anthropic Claude 3 Opus 2024-02-29 快照版本, 200K 上下文, 旗舰级推理能力。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-opus-20240229 | 2024-02-29 | 200K | text, image | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 85.7 | % | 5-shot |
| HumanEval | 79.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.3 | % | 0-shot CoT |
| MATH | 58.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.5 | % | 3-shot CoT |
| GPQA | 38.6 | % | 0-shot |
| IFEval | 75.5 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 57.3 | % | 0-shot |
| WinoGrande | 87.8 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- MMLU score 85.7, strong knowledge reasoning.
- Input Modalities: text, image, audio.
- Context window 200K.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Long document summarization
- Vision and image understanding
- Agent workflows and tool use

## References

- [Claude 3 Opus (2024-02-29) Documentation](https://docs.anthropic.com/claude/docs)
- Release Date: 2024-02-29
- Vendor: Anthropic
