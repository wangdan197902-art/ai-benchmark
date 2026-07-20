---
title: "Gemma 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemma 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-21
lastmod: 2024-02-21
draft: false
weight: 10
model_id: "gemma-7b"
vendor: "google"
version: "gemma-7b"
tags: ["open-weights", "self-hostable"]
---

# Gemma 7B

## Przegląd modelu

Google Gemma 7B 开源模型, 8K 上下文, 基于 Gemini 技术, 在 7B 规模上达到 Llama 2 13B 性能。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | gemma-7b | 2024-02-21 | 8K | text | text | Gemma License |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.6 | % | 5-shot |
| HumanEval | 61.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.6 | % | 0-shot CoT |
| MATH | 25.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.7 | % | 3-shot CoT |
| GPQA | 37.1 | % | 0-shot |
| IFEval | 66.9 | % | prompt_strict |
| ARC | 88.4 | % | challenge |
| MUSR | 36.2 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

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

- [Gemma 7B Dokumentacja](https://ai.google.dev/gemma/docs)
- Data wydania: 2024-02-21
- Dostawca: Google
