---
title: "Claude 3 Haiku vs Claude 3 Sonnet: Benchmark Comparison"
description: "Detailed comparison of Claude 3 Haiku and Claude 3 Sonnet covering benchmarks, pricing, context window, and compliance."
date: 2024-03-07
lastmod: 2024-03-07
draft: false
weight: 10
comparison_id: "claude-3-haiku-vs-claude-3-sonnet"
models: ["claude-3-haiku", "claude-3-sonnet"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "anthropic", "anthropic"]
---

# Claude 3 Haiku contra Claude 3 Sonnet

## Visão geral do modelo

Claude 3 Haiku and Claude 3 Sonnet are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Especificações principais

| Fornecedor | Data de lançamento | Janela de contexto | Licença |
|---------|-------------|----------------|---------|
| Anthropic / Anthropic | 2024-03-07 / 2024-03-04 | 200K / 200K | Proprietary / Proprietary |

## Desempenho em benchmarks

| Benchmark | Claude 3 Haiku | Claude 3 Sonnet | Vencedor |
|------|------|------|--------|
| ARC | 94.3 | 94.8 | B |
| BBH (BIG-Bench Hard) | 75.7 | 76.1 | Tie |
| GPQA | 44.4 | 35.9 | A |
| GSM8K (Grade School Math 8K) | 82.2 | 84.0 | B |
| HumanEval | 69.4 | 74.5 | B |
| IFEval | 70.8 | 74.3 | B |
| MATH | 52.2 | 42.4 | A |
| MMLU (Massive Multitask Language Understanding) | 77.9 | 81.5 | B |
| MUSR | 58.1 | 64.1 | B |
| WinoGrande | 84.8 | 83.8 | A |

## Comparação de preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*por milhão de tokens — A / B*

## Pontos fortes & Pontos fracos

### Claude 3 Haiku

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。

### Claude 3 Sonnet

- ✅ MMLU score 81.5, strong knowledge reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

## Opinião do editor

Claude 3 Haiku and Claude 3 Sonnet each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Perguntas frequentes

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referências

- [Claude 3 Haiku Documentação](https://docs.anthropic.com/claude/docs)
- [Claude 3 Sonnet Documentação](https://docs.anthropic.com/claude/docs)
