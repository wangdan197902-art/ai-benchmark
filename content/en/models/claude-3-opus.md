---
title: "Claude 3 Opus: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Opus performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-04
lastmod: 2024-03-04
draft: false
weight: 10
model_id: "claude-3-opus"
vendor: "anthropic"
version: "3-opus"
tags: ["flagship", "multimodal", "long-context"]
---

# Claude 3 Opus

## Model Overview

Anthropic Claude 3 Opus 旗舰模型, 200K 上下文, 超越 GPT-4 的推理与创意能力, 适合复杂分析任务。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-opus | 2024-03-04 | 200K | text, image | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.2 | % | 5-shot |
| HumanEval | 83.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 91.8 | % | 0-shot CoT |
| MATH | 42.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 81.6 | % | 3-shot CoT |
| GPQA | 46.0 | % | 0-shot |
| IFEval | 79.2 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 53.3 | % | 0-shot |
| WinoGrande | 81.9 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- MMLU score 81.2, strong knowledge reasoning.
- HumanEval 83.3, excellent code generation.
- GSM8K 91.8, robust math reasoning.
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

- [Claude 3 Opus Documentation](https://docs.anthropic.com/claude/docs)
- Release Date: 2024-03-04
- Vendor: Anthropic
