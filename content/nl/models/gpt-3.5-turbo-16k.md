---
title: "GPT-3.5 Turbo 16K: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-3.5 Turbo 16K performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-06-13
lastmod: 2023-06-13
draft: false
weight: 10
model_id: "gpt-3.5-turbo-16k"
vendor: "openai"
version: "3.5-turbo-16k"
tags: ["legacy", "long-context"]
---

# GPT-3.5 Turbo 16K

## Modeloverzicht

OpenAI GPT-3.5 Turbo 16K 长上下文版本, 支持 16385 token, 适合中等长度文档处理。

## Kernspecificaties

| Leverancier | Versie | Releasedatum | Contextvenster | Invoermodaliteiten | Uitvoermodaliteiten | Licentie |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 3.5-turbo-16k | 2023-06-13 | 16K | text | text | Proprietary |

## Benchmarkprestaties

| Benchmark | Score | Eenheid | Notities |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.2 | % | 5-shot |
| HumanEval | 36.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 52.8 | % | 0-shot CoT |
| MATH | 30.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.2 | % | 3-shot CoT |
| GPQA | 21.6 | % | 0-shot |
| IFEval | 48.5 | % | prompt_strict |
| ARC | 83.1 | % | challenge |
| MUSR | 29.1 | % | 0-shot |
| WinoGrande | 74.0 | % | 0-shot |

## Prijzen

| Invoer | Uitvoer | Cache-lezen | Cache-schrijven |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljoen tokens*

## Sterktes

- 上下文窗口 16K，支持长文本。

## Zwaktes

- HumanEval 36.8，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Gebruiksscenario's

- 长文档摘要

## Referenties

- [GPT-3.5 Turbo 16K Documentatie](https://platform.openai.com/docs/models)
- Releasedatum: 2023-06-13
- Leverancier: Openai
