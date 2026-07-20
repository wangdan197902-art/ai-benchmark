---
title: "Llama 3.1 Nemotron 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.1 Nemotron 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-17
lastmod: 2024-10-17
draft: false
weight: 10
model_id: "llama-3-1-nemotron-70b"
vendor: "meta"
version: "3.1-nemotron-70b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Llama 3.1 Nemotron 70B

## Przegląd modelu

Meta/NVIDIA Llama 3.1 Nemotron 70B, 128K 上下文, NVIDIA 优化版本, 在 Arena 排行榜上接近 GPT-4o。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.1-nemotron-70b | 2024-10-17 | 128K | text | text | Llama 3.1 Community License |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.5 | % | 5-shot |
| HumanEval | 79.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.6 | % | 0-shot CoT |
| MATH | 40.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.3 | % | 3-shot CoT |
| GPQA | 42.6 | % | 0-shot |
| IFEval | 74.5 | % | prompt_strict |
| ARC | 93.7 | % | challenge |
| MUSR | 54.1 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- MMLU score 81.5, strong knowledge reasoning.

## Słabe strony

- 闭源专有模型，不支持自托管。

## Przypadki użycia

- 代码生成与调试

## Referencje

- [Llama 3.1 Nemotron 70B Dokumentacja](https://llama.meta.com/docs/)
- Data wydania: 2024-10-17
- Dostawca: Meta
