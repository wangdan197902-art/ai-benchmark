---
title: "Llama 3.2 11B Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.2 11B Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-25
lastmod: 2024-09-25
draft: false
weight: 10
model_id: "llama-3-2-11b-vision"
vendor: "meta"
version: "3.2-11b-vision"
tags: ["open-weights", "multimodal", "self-hostable"]
---

# Llama 3.2 11B Vision

## Przegląd modelu

Meta Llama 3.2 11B Vision 经济型多模态开源模型, 128K 上下文, 11B 参数, 适合边缘视觉任务。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.2-11b-vision | 2024-09-25 | 128K | text, image | text | Llama 3.2 Community License |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 61.9 | % | 5-shot |
| HumanEval | 50.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 68.2 | % | 0-shot CoT |
| MATH | 29.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 69.1 | % | 3-shot CoT |
| GPQA | 35.5 | % | 0-shot |
| IFEval | 58.4 | % | prompt_strict |
| ARC | 86.0 | % | challenge |
| MUSR | 41.7 | % | 0-shot |
| WinoGrande | 72.7 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- 支持文本、图像、音频多模态输入。

## Słabe strony

- 闭源专有模型，不支持自托管。

## Przypadki użycia

- 视觉与图像理解

## Referencje

- [Llama 3.2 11B Vision Dokumentacja](https://llama.meta.com/docs/)
- Data wydania: 2024-09-25
- Dostawca: Meta
