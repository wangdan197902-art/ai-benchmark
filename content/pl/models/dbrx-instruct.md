---
title: "DBRX Instruct: Complete Benchmark Performance Guide"
description: "In-depth analysis of DBRX Instruct performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-27
lastmod: 2024-03-27
draft: false
weight: 10
model_id: "dbrx-instruct"
vendor: "other"
version: "dbrx-instruct"
tags: ["open-weights", "moe", "self-hostable"]
---

# DBRX Instruct

## Przegląd modelu

Databricks DBRX Instruct MoE 模型, 32K 上下文, 总参 132B/活跃 36B, 在开源模型中编程/数学领先。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | dbrx-instruct | 2024-03-27 | 32K | text | text | DBRX Open Model License |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.3 | % | 5-shot |
| HumanEval | 72.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.7 | % | 0-shot CoT |
| MATH | 50.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.7 | % | 3-shot CoT |
| GPQA | 34.7 | % | 0-shot |
| IFEval | 73.1 | % | prompt_strict |
| ARC | 93.9 | % | challenge |
| MUSR | 54.7 | % | 0-shot |
| WinoGrande | 81.8 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- MMLU score 81.3, strong knowledge reasoning.
- 采用 MoE 混合专家架构。

## Słabe strony

- 闭源专有模型，不支持自托管。

## Przypadki użycia

- 代码生成与调试

## Referencje

- [DBRX Instruct Dokumentacja](https://huggingface.co/models)
- Data wydania: 2024-03-27
- Dostawca: Other
