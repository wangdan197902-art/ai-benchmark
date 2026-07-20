---
title: "Qwen2.5 72B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2.5 72B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-72b"
vendor: "alibaba"
version: "2.5-72b"
tags: ["open-weights", "chinese", "coding"]
---

# Qwen2.5 72B

## Modeloverzicht

阿里巴巴通义千问 Qwen2.5 72B 开源模型，131K 上下文窗口，在中文理解、代码生成与数学推理上表现突出，是当前最强的中文开源模型之一。

## Kernspecificaties

| Leverancier | Versie | Releasedatum | Contextvenster | Invoermodaliteiten | Uitvoermodaliteiten | Licentie |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-72b | 2024-09-19 | 131K | text | text | Qwen License |

## Benchmarkprestaties

| Benchmark | Score | Eenheid | Notities |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 86.1 | % | 5-shot |
| HumanEval | 86.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 88.4 | % | 0-shot CoT |
| MATH | 83.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.4 | % | 3-shot CoT |

## Prijzen

| Invoer | Uitvoer | Cache-lezen | Cache-schrijven |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljoen tokens*

## Sterktes

- MMLU score 86.1, strong knowledge reasoning.
- HumanEval 86.6, excellent code generation.
- GSM8K 88.4, robust math reasoning.

## Zwaktes

- 闭源专有模型，不支持自托管。

## Gebruiksscenario's

- 代码生成与调试

## Referenties

- [Qwen2.5 72B Documentatie](https://qwenlm.github.io/)
- Releasedatum: 2024-09-19
- Leverancier: Alibaba
