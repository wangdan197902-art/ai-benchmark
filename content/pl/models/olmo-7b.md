---
title: "OLMo 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of OLMo 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-01
lastmod: 2024-02-01
draft: false
weight: 10
model_id: "olmo-7b"
vendor: "other"
version: "olmo-7b"
tags: ["open-weights", "self-hostable"]
---

# OLMo 7B

## Przegląd modelu

AllenAI OLMo 7B 完全开源模型, 2K 上下文, 训练数据/代码/权重全部开放, 适合研究用途。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | olmo-7b | 2024-02-01 | 2K | text | text | Apache 2.0 |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 62.6 | % | 5-shot |
| HumanEval | 62.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 71.3 | % | 0-shot CoT |
| MATH | 37.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 67.7 | % | 3-shot CoT |
| GPQA | 37.4 | % | 0-shot |
| IFEval | 68.4 | % | prompt_strict |
| ARC | 86.4 | % | challenge |
| MUSR | 46.8 | % | 0-shot |
| WinoGrande | 78.7 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- 可靠的通用模型。

## Słabe strony

- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## Przypadki użycia

- 通用对话与问答

## Referencje

- [OLMo 7B Dokumentacja](https://huggingface.co/models)
- Data wydania: 2024-02-01
- Dostawca: Other
