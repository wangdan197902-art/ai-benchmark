---
title: "Qwen2 72B vs Qwen2.5 72B: Benchmark Comparison"
description: "Detailed comparison of Qwen2 72B and Qwen2.5 72B covering benchmarks, pricing, context window, and compliance."
date: 2024-06-07
lastmod: 2024-06-07
draft: false
weight: 10
comparison_id: "qwen2-72b-vs-qwen2-5-72b"
models: ["qwen2-72b", "qwen2-5-72b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "alibaba", "alibaba"]
---

# Qwen2 72B mot Qwen2.5 72B

## Modellöversikt

Qwen2 72B and Qwen2.5 72B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Nyckelspecifikationer

| Leverantör | Releasedatum | Kontextfönster | Licens |
|---------|-------------|----------------|---------|
| Alibaba / Alibaba | 2024-06-07 / 2024-09-19 | 131K / 131K | Qwen License / Qwen License |

## Benchmarkprestanda

| Benchmark | Qwen2 72B | Qwen2.5 72B | Vinnare |
|------|------|------|--------|
| ARC | 94.4 | — | A |
| BBH (BIG-Bench Hard) | 83.4 | 82.4 | A |
| GPQA | 53.6 | — | A |
| GSM8K (Grade School Math 8K) | 87.0 | 88.4 | B |
| HumanEval | 76.5 | 86.6 | B |
| IFEval | 76.9 | — | A |
| MATH | 71.9 | 83.1 | B |
| MMLU (Massive Multitask Language Understanding) | 80.2 | 86.1 | B |
| MUSR | 68.9 | — | A |
| WinoGrande | 82.5 | — | A |

## Prisjämförelse

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*per miljon tokens — A / B*

## Styrkor & Svagheter

### Qwen2 72B

- ✅ MMLU score 80.2, strong knowledge reasoning.
- ✅ GSM8K 87.0, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### Qwen2.5 72B

- ✅ MMLU score 86.1, strong knowledge reasoning.
- ✅ HumanEval 86.6, excellent code generation.
- ✅ GSM8K 88.4, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## Redaktörens åsikt

Qwen2 72B and Qwen2.5 72B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Vanliga frågor

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referenser

- [Qwen2 72B Dokumentation](https://qwenlm.github.io/)
- [Qwen2.5 72B Dokumentation](https://qwenlm.github.io/)
