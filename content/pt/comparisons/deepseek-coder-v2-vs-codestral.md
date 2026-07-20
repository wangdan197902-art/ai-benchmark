---
title: "DeepSeek Coder V2 vs Codestral: Benchmark Comparison"
description: "Detailed comparison of DeepSeek Coder V2 and Codestral covering benchmarks, pricing, context window, and compliance."
date: 2024-06-21
lastmod: 2024-06-21
draft: false
weight: 10
comparison_id: "deepseek-coder-v2-vs-codestral"
models: ["deepseek-coder-v2", "codestral"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "deepseek", "mistral"]
---

# DeepSeek Coder V2 contra Codestral

## Visão geral do modelo

DeepSeek Coder V2 and Codestral are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Especificações principais

| Fornecedor | Data de lançamento | Janela de contexto | Licença |
|---------|-------------|----------------|---------|
| Deepseek / Mistral | 2024-06-21 / 2024-05-29 | 128K / 32K | DeepSeek License / MNPL |

## Desempenho em benchmarks

| Benchmark | DeepSeek Coder V2 | Codestral | Vencedor |
|------|------|------|--------|
| ARC | 88.5 | 87.4 | A |
| BBH (BIG-Bench Hard) | 72.3 | 58.3 | A |
| GPQA | 25.4 | 32.4 | B |
| GSM8K (Grade School Math 8K) | 62.9 | 63.3 | Tie |
| HumanEval | 88.9 | 69.2 | A |
| IFEval | 56.7 | 59.4 | B |
| MATH | 38.2 | 29.4 | A |
| MMLU (Massive Multitask Language Understanding) | 72.3 | 75.1 | B |
| MUSR | 40.3 | 47.2 | B |
| WinoGrande | 78.8 | 75.8 | A |

## Comparação de preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*por milhão de tokens — A / B*

## Pontos fortes & Pontos fracos

### DeepSeek Coder V2

- ✅ HumanEval 88.9, excellent code generation.
- ✅ 采用 MoE 混合专家架构。
- ⚠️ 闭源专有模型，不支持自托管。

### Codestral

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。

## Opinião do editor

DeepSeek Coder V2 and Codestral each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Perguntas frequentes

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referências

- [DeepSeek Coder V2 Documentação](https://api-docs.deepseek.com/)
- [Codestral Documentação](https://docs.mistral.ai/)
