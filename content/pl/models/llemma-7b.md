---
title: "Llemma 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llemma 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-10-17
lastmod: 2023-10-17
draft: false
weight: 10
model_id: "llemma-7b"
vendor: "other"
version: "llemma-7b"
tags: ["open-weights", "math", "self-hostable"]
---

# Llemma 7B

## Przegląd modelu

TheBloke Llemma 7B 数学专用模型, 4K 上下文, 基于 Code Llama 7B 继续训练, 数学推理能力突出。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | llemma-7b | 2023-10-17 | 4K | text | text | Apache 2.0 |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 66.0 | % | 5-shot |
| HumanEval | 64.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.9 | % | 0-shot CoT |
| MATH | 47.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 73.1 | % | 3-shot CoT |
| GPQA | 37.4 | % | 0-shot |
| IFEval | 52.9 | % | prompt_strict |
| ARC | 87.4 | % | challenge |
| MUSR | 42.6 | % | 0-shot |
| WinoGrande | 70.8 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- 可靠的通用模型。

## Słabe strony

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Przypadki użycia

- 通用对话与问答

## Referencje

- [Llemma 7B Dokumentacja](https://huggingface.co/models)
- Data wydania: 2023-10-17
- Dostawca: Other
