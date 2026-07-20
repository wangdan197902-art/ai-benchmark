---
title: "o1 vs o1 mini: Benchmark Comparison"
description: "Detailed comparison of o1 and o1 mini covering benchmarks, pricing, context window, and compliance."
date: 2024-12-17
lastmod: 2024-12-17
draft: false
weight: 10
comparison_id: "o1-vs-o1-mini"
models: ["o1", "o1-mini"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "openai"]
---

# o1 mot o1 mini

## Modellöversikt

o1 and o1 mini are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Nyckelspecifikationer

| Leverantör | Releasedatum | Kontextfönster | Licens |
|---------|-------------|----------------|---------|
| Openai / Openai | 2024-12-17 / 2024-09-12 | 200K / 128K | Proprietary / Proprietary |

## Benchmarkprestanda

| Benchmark | o1 | o1 mini | Vinnare |
|------|------|------|--------|
| ARC | 96.8 | 93.7 | A |
| BBH (BIG-Bench Hard) | 83.1 | 77.2 | A |
| GPQA | 57.5 | 40.8 | A |
| GSM8K (Grade School Math 8K) | 88.9 | 86.6 | A |
| HumanEval | 85.3 | 78.0 | A |
| IFEval | 82.2 | 73.1 | A |
| MATH | 55.7 | 44.2 | A |
| MMLU (Massive Multitask Language Understanding) | 86.3 | 78.2 | A |
| MUSR | 71.8 | 54.0 | A |
| WinoGrande | 86.7 | 78.3 | A |

## Prisjämförelse

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*per miljon tokens — A / B*

## Styrkor & Svagheter

### o1

- ✅ MMLU score 86.3, strong knowledge reasoning.
- ✅ HumanEval 85.3, excellent code generation.
- ✅ GSM8K 88.9, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### o1 mini

- ✅ GSM8K 86.6, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## Redaktörens åsikt

o1 and o1 mini each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Vanliga frågor

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referenser

- [o1 Dokumentation](https://platform.openai.com/docs/models)
- [o1 mini Dokumentation](https://platform.openai.com/docs/models)
