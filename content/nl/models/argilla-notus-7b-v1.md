---
title: "Argilla Notus 7B v1: Complete Benchmark Performance Guide"
description: "In-depth analysis of Argilla Notus 7B v1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-15
lastmod: 2023-12-15
draft: false
weight: 10
model_id: "argilla-notus-7b-v1"
vendor: "other"
version: "notus-7b-v1"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Argilla Notus 7B v1

## Modeloverzicht

Argilla Notus 7B v1 对话微调模型, 4K 上下文, 基于 Zephyr 改进, 通过高质量反馈数据提升性能。

## Kernspecificaties

| Leverancier | Versie | Releasedatum | Contextvenster | Invoermodaliteiten | Uitvoermodaliteiten | Licentie |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | notus-7b-v1 | 2023-12-15 | 4K | text | text | Apache 2.0 |

## Benchmarkprestaties

| Benchmark | Score | Eenheid | Notities |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 71.4 | % | 5-shot |
| HumanEval | 36.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 58.8 | % | 0-shot CoT |
| MATH | 31.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.4 | % | 3-shot CoT |
| GPQA | 32.7 | % | 0-shot |
| IFEval | 42.8 | % | prompt_strict |
| ARC | 89.8 | % | challenge |
| MUSR | 30.1 | % | 0-shot |
| WinoGrande | 69.8 | % | 0-shot |

## Prijzen

| Invoer | Uitvoer | Cache-lezen | Cache-schrijven |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljoen tokens*

## Sterktes

- 可靠的通用模型。

## Zwaktes

- HumanEval 36.8，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Gebruiksscenario's

- 通用对话与问答

## Referenties

- [Argilla Notus 7B v1 Documentatie](https://huggingface.co/models)
- Releasedatum: 2023-12-15
- Leverancier: Other
