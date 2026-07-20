---
title: "Zephyr ORPO 141B Alpha: Complete Benchmark Performance Guide"
description: "In-depth analysis of Zephyr ORPO 141B Alpha performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-22
lastmod: 2024-03-22
draft: false
weight: 10
model_id: "zephyr-orpo-141b-alpha"
vendor: "other"
version: "zephyr-orpo-141b-alpha"
tags: ["open-weights", "moe", "self-hostable"]
---

# Zephyr ORPO 141B Alpha

## Visão geral do modelo

HuggingFaceH4 Zephyr ORPO 141B Alpha, 4K 上下文, 基于 Mixtral 8x22B ORPO 微调, 性能接近 GPT-4。

## Especificações principais

| Fornecedor | Versão | Data de lançamento | Janela de contexto | Modalidades de entrada | Modalidades de saída | Licença |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | zephyr-orpo-141b-alpha | 2024-03-22 | 4K | text | text | Apache 2.0 |

## Desempenho em benchmarks

| Benchmark | Pontuação | Unidade | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.5 | % | 5-shot |
| HumanEval | 74.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 80.6 | % | 0-shot CoT |
| MATH | 36.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.3 | % | 3-shot CoT |
| GPQA | 36.8 | % | 0-shot |
| IFEval | 69.7 | % | prompt_strict |
| ARC | 91.4 | % | challenge |
| MUSR | 57.7 | % | 0-shot |
| WinoGrande | 79.7 | % | 0-shot |

## Preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*por milhão de tokens*

## Pontos fortes

- 采用 MoE 混合专家架构。

## Pontos fracos

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Casos de uso

- 代码生成与调试

## Referências

- [Zephyr ORPO 141B Alpha Documentação](https://huggingface.co/models)
- Data de lançamento: 2024-03-22
- Fornecedor: Other
