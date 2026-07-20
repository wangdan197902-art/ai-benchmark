---
title: "GPT-4 32K: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 32K performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-03-14
lastmod: 2023-03-14
draft: false
weight: 10
model_id: "gpt-4-32k"
vendor: "openai"
version: "4-32k"
tags: ["flagship", "long-context", "reasoning"]
---

# GPT-4 32K

## Model Overview

OpenAI GPT-4 32K 上下文版本, 支持 32768 token 长文本输入, 适合长文档理解与生成任务。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-32k | 2023-03-14 | 32K | text | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.8 | % | 5-shot |
| HumanEval | 76.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 81.6 | % | 0-shot CoT |
| MATH | 40.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.2 | % | 3-shot CoT |
| GPQA | 40.9 | % | 0-shot |
| IFEval | 74.7 | % | prompt_strict |
| ARC | 95.0 | % | challenge |
| MUSR | 54.9 | % | 0-shot |
| WinoGrande | 82.2 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- MMLU score 80.8, strong knowledge reasoning.
- Context window 32K.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Long document summarization
- Agent workflows and tool use

## References

- [GPT-4 32K Documentation](https://platform.openai.com/docs/models)
- Release Date: 2023-03-14
- Vendor: Openai
