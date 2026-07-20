---
title: "Llama 3.1 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.1 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-23
lastmod: 2024-07-23
draft: false
weight: 10
model_id: "llama-3-1-8b"
vendor: "meta"
version: "3.1-8b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3.1 8B

## Przegląd modelu

Meta Llama 3.1 8B 经济型开源模型, 128K 上下文, 8B 参数, 适合边缘部署与高吞吐量场景。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.1-8b | 2024-07-23 | 128K | text | text | Llama 3 Community License |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 73.0 | % | 5-shot |
| HumanEval | 63.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 58.8 | % | 0-shot CoT |
| MATH | 31.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 67.1 | % | 3-shot CoT |
| GPQA | 34.8 | % | 0-shot |
| IFEval | 62.1 | % | prompt_strict |
| ARC | 87.4 | % | challenge |
| MUSR | 41.7 | % | 0-shot |
| WinoGrande | 77.6 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- 可靠的通用模型。

## Słabe strony

- 闭源专有模型，不支持自托管。

## Przypadki użycia

- 通用对话与问答

## Referencje

- [Llama 3.1 8B Dokumentacja](https://llama.meta.com/docs/)
- Data wydania: 2024-07-23
- Dostawca: Meta
