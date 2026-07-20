---
title: "DeepSeek V2 vs DeepSeek V3: Benchmark Comparison"
description: "Detailed comparison of DeepSeek V2 and DeepSeek V3 covering benchmarks, pricing, context window, and compliance."
date: 2024-05-07
lastmod: 2024-05-07
draft: false
weight: 10
comparison_id: "deepseek-v2-vs-deepseek-v3"
models: ["deepseek-v2", "deepseek-v3"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "deepseek", "deepseek"]
---

# DeepSeek V2 contra DeepSeek V3

## Visão geral do modelo

DeepSeek V2 and DeepSeek V3 are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Especificações principais

| Fornecedor | Data de lançamento | Janela de contexto | Licença |
|---------|-------------|----------------|---------|
| Deepseek / Deepseek | 2024-05-07 / 2024-12-26 | 32K / 64K | DeepSeek License / DeepSeek License |

## Desempenho em benchmarks

| Benchmark | DeepSeek V2 | DeepSeek V3 | Vencedor |
|------|------|------|--------|
| ARC | 92.1 | — | A |
| BBH (BIG-Bench Hard) | 70.5 | 84.9 | B |
| GPQA | 31.5 | — | A |
| GSM8K (Grade School Math 8K) | 78.8 | 89.3 | B |
| HumanEval | 75.7 | 82.6 | B |
| IFEval | 78.6 | — | A |
| MATH | 35.2 | 61.6 | B |
| MMLU (Massive Multitask Language Understanding) | 78.2 | 88.5 | B |
| MUSR | 53.4 | — | A |
| WinoGrande | 84.7 | — | A |

## Comparação de preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*por milhão de tokens — A / B*

## Pontos fortes & Pontos fracos

### DeepSeek V2

- ✅ 采用 MoE 混合专家架构。
- ⚠️ 闭源专有模型，不支持自托管。

### DeepSeek V3

- ✅ MMLU score 88.5, strong knowledge reasoning.
- ✅ HumanEval 82.6, excellent code generation.
- ✅ GSM8K 89.3, robust math reasoning.
- ✅ 采用 MoE 混合专家架构。
- ⚠️ 闭源专有模型，不支持自托管。

## Opinião do editor

DeepSeek V2 and DeepSeek V3 each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Perguntas frequentes

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referências

- [DeepSeek V2 Documentação](https://api-docs.deepseek.com/)
- [DeepSeek V3 Documentação](https://api-docs.deepseek.com/)
