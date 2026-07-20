---
title: "MPT 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of MPT 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-05-04
lastmod: 2023-05-04
draft: false
weight: 10
model_id: "mpt-7b"
vendor: "other"
version: "mpt-7b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# MPT 7B

## Modeloverzicht

MosaicML MPT 7B 经济型开源模型, 2K 上下文, 7B 参数, Apache 2.0 可商用, 适合本地部署。

## Kernspecificaties

| Leverancier | Versie | Releasedatum | Contextvenster | Invoermodaliteiten | Uitvoermodaliteiten | Licentie |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | mpt-7b | 2023-05-04 | 2K | text | text | Apache 2.0 |

## Benchmarkprestaties

| Benchmark | Score | Eenheid | Notities |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.7 | % | 5-shot |
| HumanEval | 38.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 44.6 | % | 0-shot CoT |
| MATH | 18.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 59.9 | % | 3-shot CoT |
| GPQA | 34.2 | % | 0-shot |
| IFEval | 59.9 | % | prompt_strict |
| ARC | 87.5 | % | challenge |
| MUSR | 42.4 | % | 0-shot |
| WinoGrande | 65.5 | % | 0-shot |

## Prijzen

| Invoer | Uitvoer | Cache-lezen | Cache-schrijven |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljoen tokens*

## Sterktes

- 可靠的通用模型。

## Zwaktes

- MMLU 仅 51.7，知识推理偏弱。
- HumanEval 38.1，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## Gebruiksscenario's

- 通用对话与问答

## Referenties

- [MPT 7B Documentatie](https://huggingface.co/models)
- Releasedatum: 2023-05-04
- Leverancier: Other
