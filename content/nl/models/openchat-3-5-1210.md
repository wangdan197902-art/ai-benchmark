---
title: "OpenChat 3.5 1210: Complete Benchmark Performance Guide"
description: "In-depth analysis of OpenChat 3.5 1210 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-10
lastmod: 2023-12-10
draft: false
weight: 10
model_id: "openchat-3-5-1210"
vendor: "other"
version: "openchat-3-5-1210"
tags: ["open-weights", "self-hostable", "legacy"]
---

# OpenChat 3.5 1210

## Modeloverzicht

OpenChat 3.5 1210 对话模型, 8K 上下文, 基于 Mistral 7B C-RLFT 微调, 性能超越 ChatGPT 3.5。

## Kernspecificaties

| Leverancier | Versie | Releasedatum | Contextvenster | Invoermodaliteiten | Uitvoermodaliteiten | Licentie |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | openchat-3-5-1210 | 2023-12-10 | 8K | text | text | Apache 2.0 |

## Benchmarkprestaties

| Benchmark | Score | Eenheid | Notities |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 70.5 | % | 5-shot |
| HumanEval | 41.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 55.0 | % | 0-shot CoT |
| MATH | 15.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.4 | % | 3-shot CoT |
| GPQA | 20.9 | % | 0-shot |
| IFEval | 50.4 | % | prompt_strict |
| ARC | 88.1 | % | challenge |
| MUSR | 32.6 | % | 0-shot |
| WinoGrande | 69.3 | % | 0-shot |

## Prijzen

| Invoer | Uitvoer | Cache-lezen | Cache-schrijven |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljoen tokens*

## Sterktes

- 可靠的通用模型。

## Zwaktes

- HumanEval 41.9，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Gebruiksscenario's

- 通用对话与问答

## Referenties

- [OpenChat 3.5 1210 Documentatie](https://huggingface.co/models)
- Releasedatum: 2023-12-10
- Leverancier: Other
