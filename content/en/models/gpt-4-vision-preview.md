---
title: "GPT-4 Vision Preview: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 Vision Preview performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-25
lastmod: 2023-09-25
draft: false
weight: 10
model_id: "gpt-4-vision-preview"
vendor: "openai"
version: "4-vision-preview"
tags: ["multimodal", "flagship"]
---

# GPT-4 Vision Preview

## Model Overview

OpenAI GPT-4 Vision 预览版, 支持图像输入理解, 128K 上下文, 多模态能力首次集成。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-vision-preview | 2023-09-25 | 128K | text, image | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 85.0 | % | 5-shot |
| HumanEval | 70.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.5 | % | 0-shot CoT |
| MATH | 49.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.0 | % | 3-shot CoT |
| GPQA | 36.3 | % | 0-shot |
| IFEval | 72.7 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 64.5 | % | 0-shot |
| WinoGrande | 80.6 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- MMLU score 85.0, strong knowledge reasoning.
- Input Modalities: text, image, audio.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Vision and image understanding
- Agent workflows and tool use

## References

- [GPT-4 Vision Preview Documentation](https://platform.openai.com/docs/models)
- Release Date: 2023-09-25
- Vendor: Openai
