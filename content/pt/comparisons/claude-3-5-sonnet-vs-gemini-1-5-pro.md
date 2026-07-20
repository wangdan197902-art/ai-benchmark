---
title: "Claude 3.5 Sonnet vs Gemini 1.5 Pro: Benchmark Comparison"
description: "Detailed comparison of Claude 3.5 Sonnet and Gemini 1.5 Pro covering benchmarks, pricing, context window, and compliance."
date: 2024-06-20
lastmod: 2024-06-20
draft: false
weight: 10
comparison_id: "claude-3-5-sonnet-vs-gemini-1-5-pro"
models: ["claude-3-5-sonnet", "gemini-1-5-pro"]
benchmarks: ["bbh", "gsm8k", "humaneval", "math", "mmlu"]
verdict: "See Editor's Take section."
tags: ["comparison", "anthropic", "google"]
---

# Claude 3.5 Sonnet contra Gemini 1.5 Pro

## Visão geral do modelo

Claude 3.5 Sonnet and Gemini 1.5 Pro are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Especificações principais

| Fornecedor | Data de lançamento | Janela de contexto | Licença |
|---------|-------------|----------------|---------|
| Anthropic / Google | 2024-06-20 / 2024-02-15 | 200K / 2000K | Proprietary / Proprietary |

## Desempenho em benchmarks

| Benchmark | Claude 3.5 Sonnet | Gemini 1.5 Pro | Vencedor |
|------|------|------|--------|
| BBH (BIG-Bench Hard) | 84.5 | 84.0 | A |
| GSM8K (Grade School Math 8K) | 96.4 | 91.7 | A |
| HumanEval | 92.0 | 71.9 | A |
| MATH | 71.1 | 58.5 | A |
| MMLU (Massive Multitask Language Understanding) | 88.7 | 85.9 | A |

## Comparação de preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*por milhão de tokens — A / B*

## Pontos fortes & Pontos fracos

### Claude 3.5 Sonnet

- ✅ MMLU score 88.7, strong knowledge reasoning.
- ✅ HumanEval 92.0, excellent code generation.
- ✅ GSM8K 96.4, robust math reasoning.
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

### Gemini 1.5 Pro

- ✅ MMLU score 85.9, strong knowledge reasoning.
- ✅ GSM8K 91.7, robust math reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 2000K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

## Opinião do editor

Claude 3.5 Sonnet and Gemini 1.5 Pro each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Perguntas frequentes

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referências

- [Claude 3.5 Sonnet Documentação](https://docs.anthropic.com/claude/docs)
- [Gemini 1.5 Pro Documentação](https://ai.google.dev/gemini-api/docs)
