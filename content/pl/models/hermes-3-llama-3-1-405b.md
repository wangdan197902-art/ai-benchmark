---
title: "Hermes 3 Llama 3.1 405B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Hermes 3 Llama 3.1 405B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "hermes-3-llama-3-1-405b"
vendor: "other"
version: "hermes-3-llama-3-1-405b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Hermes 3 Llama 3.1 405B

## Przegląd modelu

NousResearch Hermes 3 Llama 3.1 405B 微调模型, 131K 上下文, 改进中立性与推理, 性能超越基座模型。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | hermes-3-llama-3-1-405b | 2024-08-12 | 131K | text | text | Llama 3.1 Community License |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.9 | % | 5-shot |
| HumanEval | 89.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 88.9 | % | 0-shot CoT |
| MATH | 65.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.1 | % | 3-shot CoT |
| GPQA | 40.5 | % | 0-shot |
| IFEval | 78.2 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 57.7 | % | 0-shot |
| WinoGrande | 86.5 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- MMLU score 83.9, strong knowledge reasoning.
- HumanEval 89.0, excellent code generation.
- GSM8K 88.9, robust math reasoning.

## Słabe strony

- 闭源专有模型，不支持自托管。

## Przypadki użycia

- 代码生成与调试

## Referencje

- [Hermes 3 Llama 3.1 405B Dokumentacja](https://huggingface.co/models)
- Data wydania: 2024-08-12
- Dostawca: Other
