---
title: "Claude 3 Sonnet: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Sonnet performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-04
lastmod: 2024-03-04
draft: false
weight: 10
model_id: "claude-3-sonnet"
vendor: "anthropic"
version: "3-sonnet"
tags: ["multimodal", "long-context"]
---

# Claude 3 Sonnet

## Model Overview

Anthropic Claude 3 Sonnet 平衡型模型, 200K 上下文, 在速度与智能间取得平衡, 适合企业级部署。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-sonnet | 2024-03-04 | 200K | text, image | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.5 | % | 5-shot |
| HumanEval | 74.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.0 | % | 0-shot CoT |
| MATH | 42.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.1 | % | 3-shot CoT |
| GPQA | 35.9 | % | 0-shot |
| IFEval | 74.3 | % | prompt_strict |
| ARC | 94.8 | % | challenge |
| MUSR | 64.1 | % | 0-shot |
| WinoGrande | 83.8 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- MMLU score 81.5, strong knowledge reasoning.
- Input Modalities: text, image, audio.
- Context window 200K.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Long document summarization
- Vision and image understanding

## References

- [Claude 3 Sonnet Documentation](https://docs.anthropic.com/claude/docs)
- Release Date: 2024-03-04
- Vendor: Anthropic
