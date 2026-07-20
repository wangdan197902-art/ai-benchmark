---
title: "DBRX Instruct: Complete Benchmark Performance Guide"
description: "In-depth analysis of DBRX Instruct performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-27
lastmod: 2024-03-27
draft: false
weight: 10
model_id: "dbrx-instruct"
vendor: "other"
version: "dbrx-instruct"
tags: ["open-weights", "moe", "self-hostable"]
---

# DBRX Instruct

## Visão geral do modelo

Databricks DBRX Instruct MoE 模型, 32K 上下文, 总参 132B/活跃 36B, 在开源模型中编程/数学领先。

## Especificações principais

| Fornecedor | Versão | Data de lançamento | Janela de contexto | Modalidades de entrada | Modalidades de saída | Licença |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | dbrx-instruct | 2024-03-27 | 32K | text | text | DBRX Open Model License |

## Desempenho em benchmarks

| Benchmark | Pontuação | Unidade | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.3 | % | 5-shot |
| HumanEval | 72.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.7 | % | 0-shot CoT |
| MATH | 50.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.7 | % | 3-shot CoT |
| GPQA | 34.7 | % | 0-shot |
| IFEval | 73.1 | % | prompt_strict |
| ARC | 93.9 | % | challenge |
| MUSR | 54.7 | % | 0-shot |
| WinoGrande | 81.8 | % | 0-shot |

## Preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*por milhão de tokens*

## Pontos fortes

- MMLU score 81.3, strong knowledge reasoning.
- 采用 MoE 混合专家架构。

## Pontos fracos

- 闭源专有模型，不支持自托管。

## Casos de uso

- 代码生成与调试

## Referências

- [DBRX Instruct Documentação](https://huggingface.co/models)
- Data de lançamento: 2024-03-27
- Fornecedor: Other
