---
title: "GPT-4 Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-25
lastmod: 2024-01-25
draft: false
weight: 10
model_id: "gpt-4-vision"
vendor: "openai"
version: "4-vision"
tags: ["multimodal", "flagship"]
---

# GPT-4 Vision

## Model Overview

OpenAI GPT-4 Vision 正式版, 支持图像理解与多模态推理, 128K 上下文窗口。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-vision | 2024-01-25 | 128K | text, image | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.9 | % | 5-shot |
| HumanEval | 75.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.6 | % | 0-shot CoT |
| MATH | 48.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 80.9 | % | 3-shot CoT |
| GPQA | 41.8 | % | 0-shot |
| IFEval | 73.5 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 51.2 | % | 0-shot |
| WinoGrande | 86.9 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- MMLU score 83.9, strong knowledge reasoning.
- Input Modalities: text, image, audio.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Vision and image understanding
- Agent workflows and tool use

## References

- [GPT-4 Vision Documentation](https://platform.openai.com/docs/models)
- Release Date: 2024-01-25
- Vendor: Openai
