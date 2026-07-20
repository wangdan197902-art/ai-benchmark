---
title: "Qwen1.5 14B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen1.5 14B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-25
lastmod: 2024-02-25
draft: false
weight: 10
model_id: "qwen1-5-14b"
vendor: "alibaba"
version: "1.5-14b"
tags: ["open-weights", "chinese"]
---

# Qwen1.5 14B

## Modeloverzicht

阿里巴巴 Qwen1.5 14B 中型开源模型, 32K 上下文, 平衡性能与资源, 适合企业级应用。

## Kernspecificaties

| Leverancier | Versie | Releasedatum | Contextvenster | Invoermodaliteiten | Uitvoermodaliteiten | Licentie |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 1.5-14b | 2024-02-25 | 32K | text | text | Qwen License |

## Benchmarkprestaties

| Benchmark | Score | Eenheid | Notities |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.4 | % | 5-shot |
| HumanEval | 65.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.0 | % | 0-shot CoT |
| MATH | 46.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.6 | % | 3-shot CoT |
| GPQA | 33.9 | % | 0-shot |
| IFEval | 79.9 | % | prompt_strict |
| ARC | 92.7 | % | challenge |
| MUSR | 58.7 | % | 0-shot |
| WinoGrande | 78.6 | % | 0-shot |

## Prijzen

| Invoer | Uitvoer | Cache-lezen | Cache-schrijven |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljoen tokens*

## Sterktes

- 可靠的通用模型。

## Zwaktes

- 闭源专有模型，不支持自托管。

## Gebruiksscenario's

- 通用对话与问答

## Referenties

- [Qwen1.5 14B Documentatie](https://qwenlm.github.io/)
- Releasedatum: 2024-02-25
- Leverancier: Alibaba
