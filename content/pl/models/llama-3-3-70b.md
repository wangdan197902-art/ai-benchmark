---
title: "Llama 3.3 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.3 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-12-06
lastmod: 2024-12-06
draft: false
weight: 10
model_id: "llama-3-3-70b"
vendor: "meta"
version: "3.3-70b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Llama 3.3 70B

## Przegląd modelu

Meta Llama 3.3 70B 开源旗舰, 128K 上下文, 性能超越 Llama 3.1 405B, 接近 GPT-4o 水平。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.3-70b | 2024-12-06 | 128K | text | text | Llama 3.3 Community License |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.4 | % | 5-shot |
| HumanEval | 87.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 86.9 | % | 0-shot CoT |
| MATH | 73.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.9 | % | 3-shot CoT |
| GPQA | 52.8 | % | 0-shot |
| IFEval | 79.3 | % | prompt_strict |
| ARC | 93.9 | % | challenge |
| MUSR | 62.3 | % | 0-shot |
| WinoGrande | 86.8 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- MMLU score 83.4, strong knowledge reasoning.
- HumanEval 87.0, excellent code generation.
- GSM8K 86.9, robust math reasoning.

## Słabe strony

- 闭源专有模型，不支持自托管。

## Przypadki użycia

- 代码生成与调试

## Referencje

- [Llama 3.3 70B Dokumentacja](https://llama.meta.com/docs/)
- Data wydania: 2024-12-06
- Dostawca: Meta
