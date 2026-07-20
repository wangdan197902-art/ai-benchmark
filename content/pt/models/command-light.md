---
title: "Command Light: Complete Benchmark Performance Guide"
description: "In-depth analysis of Command Light performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-14
lastmod: 2023-09-14
draft: false
weight: 10
model_id: "command-light"
vendor: "cohere"
version: "light"
tags: ["legacy", "realtime"]
---

# Command Light

## Visão geral do modelo

Cohere Command Light 经济型模型, 4K 上下文, 速度快成本低, 适合简单任务与高吞吐场景。

## Especificações principais

| Fornecedor | Versão | Data de lançamento | Janela de contexto | Modalidades de entrada | Modalidades de saída | Licença |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | light | 2023-09-14 | 4K | text | text | CC-BY-NC-4.0 |

## Desempenho em benchmarks

| Benchmark | Pontuação | Unidade | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 52.8 | % | 5-shot |
| HumanEval | 51.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 39.8 | % | 0-shot CoT |
| MATH | 24.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 55.5 | % | 3-shot CoT |
| GPQA | 30.1 | % | 0-shot |
| IFEval | 53.9 | % | prompt_strict |
| ARC | 85.9 | % | challenge |
| MUSR | 40.7 | % | 0-shot |
| WinoGrande | 74.7 | % | 0-shot |

## Preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*por milhão de tokens*

## Pontos fortes

- 可靠的通用模型。

## Pontos fracos

- MMLU 仅 52.8，知识推理偏弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Casos de uso

- 通用对话与问答

## Referências

- [Command Light Documentação](https://docs.cohere.com/docs)
- Data de lançamento: 2023-09-14
- Fornecedor: Cohere
