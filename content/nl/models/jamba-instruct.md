---
title: "Jamba Instruct: Complete Benchmark Performance Guide"
description: "In-depth analysis of Jamba Instruct performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-28
lastmod: 2024-03-28
draft: false
weight: 10
model_id: "jamba-instruct"
vendor: "other"
version: "jamba-instruct"
tags: ["open-weights", "long-context"]
---

# Jamba Instruct

## Modeloverzicht

AI21 Labs Jamba Instruct 指令微调模型, 256K 上下文, 首个商用 Mamba-Transformer 混合架构。

## Kernspecificaties

| Leverancier | Versie | Releasedatum | Contextvenster | Invoermodaliteiten | Uitvoermodaliteiten | Licentie |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | jamba-instruct | 2024-03-28 | 256K | text | text | Jamba Open Model License |

## Benchmarkprestaties

| Benchmark | Score | Eenheid | Notities |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.2 | % | 5-shot |
| HumanEval | 66.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.2 | % | 0-shot CoT |
| MATH | 49.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.8 | % | 3-shot CoT |
| GPQA | 37.4 | % | 0-shot |
| IFEval | 79.2 | % | prompt_strict |
| ARC | 91.2 | % | challenge |
| MUSR | 56.9 | % | 0-shot |
| WinoGrande | 78.3 | % | 0-shot |

## Prijzen

| Invoer | Uitvoer | Cache-lezen | Cache-schrijven |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljoen tokens*

## Sterktes

- 上下文窗口 256K，支持长文本。

## Zwaktes

- 闭源专有模型，不支持自托管。

## Gebruiksscenario's

- 长文档摘要

## Referenties

- [Jamba Instruct Documentatie](https://huggingface.co/models)
- Releasedatum: 2024-03-28
- Leverancier: Other
