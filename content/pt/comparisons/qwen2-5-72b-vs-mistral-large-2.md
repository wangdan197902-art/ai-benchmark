---
title: "Qwen2.5 72B vs Mistral Large 2: Benchmark Comparison"
description: "Detailed comparison of Qwen2.5 72B and Mistral Large 2 covering benchmarks, pricing, context window, and compliance."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
comparison_id: "qwen2-5-72b-vs-mistral-large-2"
models: ["qwen2-5-72b", "mistral-large-2"]
benchmarks: ["bbh", "gsm8k", "humaneval", "math", "mmlu"]
verdict: "See Editor's Take section."
tags: ["comparison", "alibaba", "mistral"]
---

# Qwen2.5 72B contra Mistral Large 2

## Visão geral do modelo

Qwen2.5 72B and Mistral Large 2 are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Especificações principais

| Fornecedor | Data de lançamento | Janela de contexto | Licença |
|---------|-------------|----------------|---------|
| Alibaba / Mistral | 2024-09-19 / 2024-07-24 | 131K / 128K | Qwen License / Mistral Research License |

## Desempenho em benchmarks

| Benchmark | Qwen2.5 72B | Mistral Large 2 | Vencedor |
|------|------|------|--------|
| BBH (BIG-Bench Hard) | 82.4 | 81.0 | A |
| GSM8K (Grade School Math 8K) | 88.4 | 93.0 | B |
| HumanEval | 86.6 | 92.0 | B |
| MATH | 83.1 | 71.0 | A |
| MMLU (Massive Multitask Language Understanding) | 86.1 | 84.0 | A |

## Comparação de preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*por milhão de tokens — A / B*

## Pontos fortes & Pontos fracos

### Qwen2.5 72B

- ✅ MMLU score 86.1, strong knowledge reasoning.
- ✅ HumanEval 86.6, excellent code generation.
- ✅ GSM8K 88.4, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### Mistral Large 2

- ✅ MMLU score 84.0, strong knowledge reasoning.
- ✅ HumanEval 92.0, excellent code generation.
- ✅ GSM8K 93.0, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## Opinião do editor

Qwen2.5 72B and Mistral Large 2 each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Perguntas frequentes

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referências

- [Qwen2.5 72B Documentação](https://qwenlm.github.io/)
- [Mistral Large 2 Documentação](https://docs.mistral.ai/)
