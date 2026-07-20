---
title: "Claude 2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-07-11
lastmod: 2023-07-11
draft: false
weight: 10
model_id: "claude-2"
vendor: "anthropic"
version: "2"
tags: ["legacy", "long-context"]
---

# Claude 2

## Visão geral do modelo

Anthropic Claude 2, 100K 上下文, 在编码/数学/推理上超越 Claude 1.3, 首次开放 API。

## Especificações principais

| Fornecedor | Versão | Data de lançamento | Janela de contexto | Modalidades de entrada | Modalidades de saída | Licença |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 2 | 2023-07-11 | 100K | text | text | Proprietary |

## Desempenho em benchmarks

| Benchmark | Pontuação | Unidade | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 66.3 | % | 5-shot |
| HumanEval | 31.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 32.5 | % | 0-shot CoT |
| MATH | 21.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.2 | % | 3-shot CoT |
| GPQA | 31.4 | % | 0-shot |
| IFEval | 55.0 | % | prompt_strict |
| ARC | 80.4 | % | challenge |
| MUSR | 35.2 | % | 0-shot |
| WinoGrande | 66.4 | % | 0-shot |

## Preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*por milhão de tokens*

## Pontos fortes

- 上下文窗口 100K，支持长文本。

## Pontos fracos

- HumanEval 31.7，代码能力较弱。
- 闭源专有模型，不支持自托管。

## Casos de uso

- 长文档摘要

## Referências

- [Claude 2 Documentação](https://docs.anthropic.com/claude/docs)
- Data de lançamento: 2023-07-11
- Fornecedor: Anthropic
