---
title: "Gemini 1.0 Pro vs Gemini 1.0 Ultra: Benchmark Comparison"
description: "Detailed comparison of Gemini 1.0 Pro and Gemini 1.0 Ultra covering benchmarks, pricing, context window, and compliance."
date: 2023-12-06
lastmod: 2023-12-06
draft: false
weight: 10
comparison_id: "gemini-1-0-pro-vs-gemini-1-0-ultra"
models: ["gemini-1-0-pro", "gemini-1-0-ultra"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "google", "google"]
---

# Gemini 1.0 Pro kontra Gemini 1.0 Ultra

## Przegląd modelu

Gemini 1.0 Pro and Gemini 1.0 Ultra are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Kluczowe specyfikacje

| Dostawca | Data wydania | Okno kontekstowe | Licencja |
|---------|-------------|----------------|---------|
| Google / Google | 2023-12-06 / 2023-12-06 | 32K / 32K | Proprietary / Proprietary |

## Wydajność benchmarków

| Benchmark | Gemini 1.0 Pro | Gemini 1.0 Ultra | Zwycięzca |
|------|------|------|--------|
| ARC | 94.1 | 95.7 | B |
| BBH (BIG-Bench Hard) | 79.1 | 83.8 | B |
| GPQA | 47.7 | 46.9 | A |
| GSM8K (Grade School Math 8K) | 82.4 | 85.9 | B |
| HumanEval | 76.4 | 81.7 | B |
| IFEval | 75.1 | 81.6 | B |
| MATH | 58.2 | 57.1 | A |
| MMLU (Massive Multitask Language Understanding) | 84.5 | 80.3 | A |
| MUSR | 57.8 | 64.3 | B |
| WinoGrande | 84.5 | 80.4 | A |

## Porównanie cen

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*za milion tokenów — A / B*

## Mocne strony & Słabe strony

### Gemini 1.0 Pro

- ✅ MMLU score 84.5, strong knowledge reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### Gemini 1.0 Ultra

- ✅ MMLU score 80.3, strong knowledge reasoning.
- ✅ HumanEval 81.7, excellent code generation.
- ✅ GSM8K 85.9, robust math reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ⚠️ 闭源专有模型，不支持自托管。

## Opinia redakcji

Gemini 1.0 Pro and Gemini 1.0 Ultra each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referencje

- [Gemini 1.0 Pro Dokumentacja](https://ai.google.dev/gemini-api/docs)
- [Gemini 1.0 Ultra Dokumentacja](https://ai.google.dev/gemini-api/docs)
