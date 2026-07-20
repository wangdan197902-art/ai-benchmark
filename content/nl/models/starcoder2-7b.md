---
title: "StarCoder2 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StarCoder2 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-28
lastmod: 2024-02-28
draft: false
weight: 10
model_id: "starcoder2-7b"
vendor: "other"
version: "starcoder2-7b"
tags: ["open-weights", "coding", "self-hostable"]
---

# StarCoder2 7B

## Modeloverzicht

BigCode StarCoder2 7B 经济型代码模型, 16K 上下文, 7B 参数, 适合本地代码补全与生成。

## Kernspecificaties

| Leverancier | Versie | Releasedatum | Contextvenster | Invoermodaliteiten | Uitvoermodaliteiten | Licentie |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | starcoder2-7b | 2024-02-28 | 16K | text | text | BigCode Open Model License |

## Benchmarkprestaties

| Benchmark | Score | Eenheid | Notities |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 67.4 | % | 5-shot |
| HumanEval | 74.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 65.0 | % | 0-shot CoT |
| MATH | 30.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.0 | % | 3-shot CoT |
| GPQA | 33.6 | % | 0-shot |
| IFEval | 54.0 | % | prompt_strict |
| ARC | 90.5 | % | challenge |
| MUSR | 38.3 | % | 0-shot |
| WinoGrande | 73.1 | % | 0-shot |

## Prijzen

| Invoer | Uitvoer | Cache-lezen | Cache-schrijven |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljoen tokens*

## Sterktes

- 可靠的通用模型。

## Zwaktes

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Gebruiksscenario's

- 代码生成与调试

## Referenties

- [StarCoder2 7B Documentatie](https://huggingface.co/models)
- Releasedatum: 2024-02-28
- Leverancier: Other
