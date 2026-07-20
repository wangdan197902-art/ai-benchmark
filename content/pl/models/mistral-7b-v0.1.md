---
title: "Mistral 7B v0.1: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral 7B v0.1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-27
lastmod: 2023-09-27
draft: false
weight: 10
model_id: "mistral-7b-v0.1"
vendor: "mistral"
version: "7b-v0.1"
tags: ["open-weights", "self-hostable"]
---

# Mistral 7B v0.1

## Przegląd modelu

Mistral 7B v0.1 首版开源模型, 8K 上下文, 7B 参数, 在所有 7B 模型中表现领先, Apache 2.0 可商用。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 7b-v0.1 | 2023-09-27 | 8K | text | text | Apache 2.0 |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 68.4 | % | 5-shot |
| HumanEval | 56.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.1 | % | 0-shot CoT |
| MATH | 26.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.4 | % | 3-shot CoT |
| GPQA | 25.3 | % | 0-shot |
| IFEval | 58.9 | % | prompt_strict |
| ARC | 88.7 | % | challenge |
| MUSR | 37.4 | % | 0-shot |
| WinoGrande | 79.6 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- 可靠的通用模型。

## Słabe strony

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Przypadki użycia

- 通用对话与问答

## Referencje

- [Mistral 7B v0.1 Dokumentacja](https://docs.mistral.ai/)
- Data wydania: 2023-09-27
- Dostawca: Mistral
