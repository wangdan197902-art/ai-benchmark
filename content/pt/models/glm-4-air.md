---
title: "GLM-4 Air: Complete Benchmark Performance Guide"
description: "In-depth analysis of GLM-4 Air performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "glm-4-air"
vendor: "other"
version: "glm-4-air"
tags: ["chinese", "realtime"]
---

# GLM-4 Air

## Visão geral do modelo

清华智谱 GLM-4 Air 经济型模型, 131K 上下文, 速度快成本低, 适合大规模部署。

## Especificações principais

| Fornecedor | Versão | Data de lançamento | Janela de contexto | Modalidades de entrada | Modalidades de saída | Licença |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | glm-4-air | 2024-08-12 | 131K | text | text | Proprietary |

## Desempenho em benchmarks

| Benchmark | Pontuação | Unidade | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.9 | % | 5-shot |
| HumanEval | 68.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.3 | % | 0-shot CoT |
| MATH | 40.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.0 | % | 3-shot CoT |
| GPQA | 31.3 | % | 0-shot |
| IFEval | 75.7 | % | prompt_strict |
| ARC | 92.3 | % | challenge |
| MUSR | 46.7 | % | 0-shot |
| WinoGrande | 78.1 | % | 0-shot |

## Preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*por milhão de tokens*

## Pontos fortes

- 可靠的通用模型。

## Pontos fracos

- 闭源专有模型，不支持自托管。

## Casos de uso

- 通用对话与问答

## Referências

- [GLM-4 Air Documentação](https://huggingface.co/models)
- Data de lançamento: 2024-08-12
- Fornecedor: Other
