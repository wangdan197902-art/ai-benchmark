---
title: "Gemini 1.5 Flash-8B 002: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.5 Flash-8B 002 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-03
lastmod: 2024-10-03
draft: false
weight: 10
model_id: "gemini-1-5-flash-8b-002"
vendor: "google"
version: "1.5-flash-8b-002"
tags: ["multimodal", "realtime"]
---

# Gemini 1.5 Flash-8B 002

## Model Overview

Google Gemini 1.5 Flash-8B 002 生产版本, 1M 上下文, 最低成本多模态推理。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.5-flash-8b-002 | 2024-10-03 | 1000K | text, image, audio, video | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.5 | % | 5-shot |
| HumanEval | 79.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 86.3 | % | 0-shot CoT |
| MATH | 43.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 73.6 | % | 3-shot CoT |
| GPQA | 39.8 | % | 0-shot |
| IFEval | 74.3 | % | prompt_strict |
| ARC | 93.2 | % | challenge |
| MUSR | 54.7 | % | 0-shot |
| WinoGrande | 84.6 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- GSM8K 86.3, robust math reasoning.
- Input Modalities: text, image, audio.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Vision and image understanding

## References

- [Gemini 1.5 Flash-8B 002 Documentation](https://ai.google.dev/gemini-api/docs)
- Release Date: 2024-10-03
- Vendor: Google
