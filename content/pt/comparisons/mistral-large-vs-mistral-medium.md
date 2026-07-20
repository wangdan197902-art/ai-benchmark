---
title: "Mistral Large vs Mistral Medium: Benchmark Comparison"
description: "Detailed comparison of Mistral Large and Mistral Medium covering benchmarks, pricing, context window, and compliance."
date: 2024-02-26
lastmod: 2024-02-26
draft: false
weight: 10
comparison_id: "mistral-large-vs-mistral-medium"
models: ["mistral-large", "mistral-medium"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "mistral", "mistral"]
---

# Mistral Large contra Mistral Medium

## Visão geral do modelo

Mistral Large and Mistral Medium are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Especificações principais

| Fornecedor | Data de lançamento | Janela de contexto | Licença |
|---------|-------------|----------------|---------|
| Mistral / Mistral | 2024-02-26 / 2023-12-11 | 32K / 32K | Apache 2.0 / Apache 2.0 |

## Desempenho em benchmarks

| Benchmark | Mistral Large | Mistral Medium | Vencedor |
|------|------|------|--------|
| ARC | 93.3 | 94.6 | B |
| BBH (BIG-Bench Hard) | 76.7 | 83.4 | B |
| GPQA | 38.1 | 48.7 | B |
| GSM8K (Grade School Math 8K) | 80.9 | 82.5 | B |
| HumanEval | 73.4 | 78.0 | B |
| IFEval | 75.8 | 77.4 | B |
| MATH | 49.3 | 54.9 | B |
| MMLU (Massive Multitask Language Understanding) | 82.0 | 82.9 | B |
| MUSR | 52.1 | 64.3 | B |
| WinoGrande | 83.3 | 82.4 | A |

## Comparação de preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*por milhão de tokens — A / B*

## Pontos fortes & Pontos fracos

### Mistral Large

- ✅ MMLU score 82.0, strong knowledge reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### Mistral Medium

- ✅ MMLU score 82.9, strong knowledge reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## Opinião do editor

Mistral Large and Mistral Medium each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Perguntas frequentes

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referências

- [Mistral Large Documentação](https://docs.mistral.ai/)
- [Mistral Medium Documentação](https://docs.mistral.ai/)
