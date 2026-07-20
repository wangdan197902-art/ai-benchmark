---
title: "Claude Instant 1: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude Instant 1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-03-14
lastmod: 2023-03-14
draft: false
weight: 10
model_id: "claude-instant-1"
vendor: "anthropic"
version: "instant-1"
tags: ["legacy"]
---

# Claude Instant 1

## Modeloverzicht

Anthropic Claude Instant 1 轻量快速模型, 9K 上下文, 价格仅为 Claude 1 的 1/5, 适合实时对话。

## Kernspecificaties

| Leverancier | Versie | Releasedatum | Contextvenster | Invoermodaliteiten | Uitvoermodaliteiten | Licentie |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | instant-1 | 2023-03-14 | 9K | text | text | Proprietary |

## Benchmarkprestaties

| Benchmark | Score | Eenheid | Notities |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 57.1 | % | 5-shot |
| HumanEval | 28.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 34.0 | % | 0-shot CoT |
| MATH | 22.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 63.1 | % | 3-shot CoT |
| GPQA | 21.8 | % | 0-shot |
| IFEval | 53.2 | % | prompt_strict |
| ARC | 80.9 | % | challenge |
| MUSR | 33.5 | % | 0-shot |
| WinoGrande | 77.2 | % | 0-shot |

## Prijzen

| Invoer | Uitvoer | Cache-lezen | Cache-schrijven |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljoen tokens*

## Sterktes

- 可靠的通用模型。

## Zwaktes

- MMLU 仅 57.1，知识推理偏弱。
- HumanEval 28.5，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 9K 偏小。

## Gebruiksscenario's

- 通用对话与问答

## Referenties

- [Claude Instant 1 Documentatie](https://docs.anthropic.com/claude/docs)
- Releasedatum: 2023-03-14
- Leverancier: Anthropic
