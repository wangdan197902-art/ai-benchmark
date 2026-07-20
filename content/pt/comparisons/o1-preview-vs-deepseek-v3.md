---
title: "o1 Preview vs DeepSeek V3: Benchmark Comparison"
description: "Detailed comparison of o1 Preview and DeepSeek V3 covering benchmarks, pricing, context window, and compliance."
date: 2024-09-12
lastmod: 2024-09-12
draft: false
weight: 10
comparison_id: "o1-preview-vs-deepseek-v3"
models: ["o1-preview", "deepseek-v3"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "deepseek"]
---

# o1 Preview contra DeepSeek V3

## Visão geral do modelo

o1 Preview and DeepSeek V3 are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Especificações principais

| Fornecedor | Data de lançamento | Janela de contexto | Licença |
|---------|-------------|----------------|---------|
| Openai / Deepseek | 2024-09-12 / 2024-12-26 | 128K / 64K | Proprietary / DeepSeek License |

## Desempenho em benchmarks

| Benchmark | o1 Preview | DeepSeek V3 | Vencedor |
|------|------|------|--------|
| ARC | 96.0 | — | A |
| BBH (BIG-Bench Hard) | 84.5 | 84.9 | Tie |
| GPQA | 57.7 | — | A |
| GSM8K (Grade School Math 8K) | 92.5 | 89.3 | A |
| HumanEval | 90.1 | 82.6 | A |
| IFEval | 84.4 | — | A |
| MATH | 71.5 | 61.6 | A |
| MMLU (Massive Multitask Language Understanding) | 85.3 | 88.5 | B |
| MUSR | 64.1 | — | A |
| WinoGrande | 85.2 | — | A |

## Comparação de preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*por milhão de tokens — A / B*

## Pontos fortes & Pontos fracos

### o1 Preview

- ✅ MMLU score 85.3, strong knowledge reasoning.
- ✅ HumanEval 90.1, excellent code generation.
- ✅ GSM8K 92.5, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### DeepSeek V3

- ✅ MMLU score 88.5, strong knowledge reasoning.
- ✅ HumanEval 82.6, excellent code generation.
- ✅ GSM8K 89.3, robust math reasoning.
- ✅ 采用 MoE 混合专家架构。
- ⚠️ 闭源专有模型，不支持自托管。

## Opinião do editor

o1 Preview and DeepSeek V3 each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Perguntas frequentes

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referências

- [o1 Preview Documentação](https://platform.openai.com/docs/models)
- [DeepSeek V3 Documentação](https://api-docs.deepseek.com/)
