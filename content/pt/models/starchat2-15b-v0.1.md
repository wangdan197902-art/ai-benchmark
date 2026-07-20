---
title: "StarChat2 15B v0.1: Complete Benchmark Performance Guide"
description: "In-depth analysis of StarChat2 15B v0.1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-05
lastmod: 2024-07-05
draft: false
weight: 10
model_id: "starchat2-15b-v0.1"
vendor: "other"
version: "starchat2-15b-v0.1"
tags: ["open-weights", "coding", "self-hostable"]
---

# StarChat2 15B v0.1

## Visão geral do modelo

HuggingFace StarChat2 15B 代码对话模型, 8K 上下文, 基于 StarCoder2 微调, 支持多语言代码生成。

## Especificações principais

| Fornecedor | Versão | Data de lançamento | Janela de contexto | Modalidades de entrada | Modalidades de saída | Licença |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | starchat2-15b-v0.1 | 2024-07-05 | 8K | text | text | BigCode Open Model License |

## Desempenho em benchmarks

| Benchmark | Pontuação | Unidade | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 74.9 | % | 5-shot |
| HumanEval | 69.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 50.7 | % | 0-shot CoT |
| MATH | 45.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.6 | % | 3-shot CoT |
| GPQA | 25.9 | % | 0-shot |
| IFEval | 63.3 | % | prompt_strict |
| ARC | 91.7 | % | challenge |
| MUSR | 44.4 | % | 0-shot |
| WinoGrande | 75.0 | % | 0-shot |

## Preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*por milhão de tokens*

## Pontos fortes

- 可靠的通用模型。

## Pontos fracos

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Casos de uso

- 代码生成与调试

## Referências

- [StarChat2 15B v0.1 Documentação](https://huggingface.co/models)
- Data de lançamento: 2024-07-05
- Fornecedor: Other
