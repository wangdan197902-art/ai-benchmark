---
title: "Ministral 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Ministral 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-16
lastmod: 2024-10-16
draft: false
weight: 10
model_id: "ministral-8b"
vendor: "mistral"
version: "ministral-8b"
tags: ["open-weights", "self-hostable", "long-context"]
---

# Ministral 8B

## Visão geral do modelo

Mistral Ministral 8B 边缘模型, 128K 上下文, 8B 参数, 为本地与边缘计算优化, 性能超越 Llama 3 8B。

## Especificações principais

| Fornecedor | Versão | Data de lançamento | Janela de contexto | Modalidades de entrada | Modalidades de saída | Licença |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | ministral-8b | 2024-10-16 | 128K | text | text | Mistral Research License |

## Desempenho em benchmarks

| Benchmark | Pontuação | Unidade | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.9 | % | 5-shot |
| HumanEval | 63.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.7 | % | 0-shot CoT |
| MATH | 39.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.0 | % | 3-shot CoT |
| GPQA | 35.1 | % | 0-shot |
| IFEval | 56.1 | % | prompt_strict |
| ARC | 85.5 | % | challenge |
| MUSR | 37.0 | % | 0-shot |
| WinoGrande | 75.3 | % | 0-shot |

## Preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*por milhão de tokens*

## Pontos fortes

- 上下文窗口 128K，支持长文本。

## Pontos fracos

- 闭源专有模型，不支持自托管。

## Casos de uso

- 长文档摘要

## Referências

- [Ministral 8B Documentação](https://docs.mistral.ai/)
- Data de lançamento: 2024-10-16
- Fornecedor: Mistral
