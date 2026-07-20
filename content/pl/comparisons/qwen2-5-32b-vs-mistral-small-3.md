---
title: "Qwen2.5 32B vs Mistral Small 3: Benchmark Comparison"
description: "Detailed comparison of Qwen2.5 32B and Mistral Small 3 covering benchmarks, pricing, context window, and compliance."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
comparison_id: "qwen2-5-32b-vs-mistral-small-3"
models: ["qwen2-5-32b", "mistral-small-3"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "alibaba", "mistral"]
---

# Qwen2.5 32B kontra Mistral Small 3

## Przegląd modelu

Qwen2.5 32B and Mistral Small 3 are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Kluczowe specyfikacje

| Dostawca | Data wydania | Okno kontekstowe | Licencja |
|---------|-------------|----------------|---------|
| Alibaba / Mistral | 2024-09-19 / 2025-01-29 | 131K / 32K | Qwen License / Apache 2.0 |

## Wydajność benchmarków

| Benchmark | Qwen2.5 32B | Mistral Small 3 | Zwycięzca |
|------|------|------|--------|
| ARC | 93.9 | 91.8 | A |
| BBH (BIG-Bench Hard) | 76.8 | 71.3 | A |
| GPQA | 39.4 | 30.1 | A |
| GSM8K (Grade School Math 8K) | 76.3 | 79.6 | B |
| HumanEval | 68.0 | 74.4 | B |
| IFEval | 73.5 | 76.9 | B |
| MATH | 39.5 | 39.2 | Tie |
| MMLU (Massive Multitask Language Understanding) | 78.5 | 76.9 | A |
| MUSR | 54.9 | 46.0 | A |
| WinoGrande | 81.9 | 78.8 | A |

## Porównanie cen

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*za milion tokenów — A / B*

## Mocne strony & Słabe strony

### Qwen2.5 32B

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。

### Mistral Small 3

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。

## Opinia redakcji

Qwen2.5 32B and Mistral Small 3 each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referencje

- [Qwen2.5 32B Dokumentacja](https://qwenlm.github.io/)
- [Mistral Small 3 Dokumentacja](https://docs.mistral.ai/)
