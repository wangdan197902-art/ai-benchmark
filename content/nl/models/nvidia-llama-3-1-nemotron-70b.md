---
title: "NVIDIA Llama 3.1 Nemotron 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of NVIDIA Llama 3.1 Nemotron 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-17
lastmod: 2024-10-17
draft: false
weight: 10
model_id: "nvidia-llama-3-1-nemotron-70b"
vendor: "other"
version: "nvidia-llama-3-1-nemotron-70b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# NVIDIA Llama 3.1 Nemotron 70B

## Modeloverzicht

NVIDIA Llama 3.1 Nemotron 70B, 131K 上下文, NVIDIA 优化 Llama 3.1, 在 Arena 上接近 GPT-4o。

## Kernspecificaties

| Leverancier | Versie | Releasedatum | Contextvenster | Invoermodaliteiten | Uitvoermodaliteiten | Licentie |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nvidia-llama-3-1-nemotron-70b | 2024-10-17 | 131K | text | text | Llama 3.1 Community License |

## Benchmarkprestaties

| Benchmark | Score | Eenheid | Notities |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.4 | % | 5-shot |
| HumanEval | 66.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.8 | % | 0-shot CoT |
| MATH | 40.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.6 | % | 3-shot CoT |
| GPQA | 37.6 | % | 0-shot |
| IFEval | 69.6 | % | prompt_strict |
| ARC | 93.2 | % | challenge |
| MUSR | 47.7 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

## Prijzen

| Invoer | Uitvoer | Cache-lezen | Cache-schrijven |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljoen tokens*

## Sterktes

- MMLU score 80.4, strong knowledge reasoning.

## Zwaktes

- 闭源专有模型，不支持自托管。

## Gebruiksscenario's

- 通用对话与问答

## Referenties

- [NVIDIA Llama 3.1 Nemotron 70B Documentatie](https://huggingface.co/models)
- Releasedatum: 2024-10-17
- Leverancier: Other
