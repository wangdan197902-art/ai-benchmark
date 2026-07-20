---
title: "Qwen2.5 3B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2.5 3B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-3b"
vendor: "alibaba"
version: "2.5-3b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Qwen2.5 3B

## Visão geral do modelo

阿里巴巴 Qwen2.5 3B 轻量开源模型, 32K 上下文, 3B 参数, 适合移动设备与边缘部署。

## Especificações principais

| Fornecedor | Versão | Data de lançamento | Janela de contexto | Modalidades de entrada | Modalidades de saída | Licença |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-3b | 2024-09-19 | 32K | text | text | Qwen License |

## Desempenho em benchmarks

| Benchmark | Pontuação | Unidade | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 56.8 | % | 5-shot |
| HumanEval | 49.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 31.3 | % | 0-shot CoT |
| MATH | 17.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.8 | % | 3-shot CoT |
| GPQA | 18.0 | % | 0-shot |
| IFEval | 56.0 | % | prompt_strict |
| ARC | 76.5 | % | challenge |
| MUSR | 23.3 | % | 0-shot |
| WinoGrande | 61.4 | % | 0-shot |

## Preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*por milhão de tokens*

## Pontos fortes

- 可靠的通用模型。

## Pontos fracos

- MMLU 仅 56.8，知识推理偏弱。
- HumanEval 49.0，代码能力较弱。
- 闭源专有模型，不支持自托管。

## Casos de uso

- 通用对话与问答

## Referências

- [Qwen2.5 3B Documentação](https://qwenlm.github.io/)
- Data de lançamento: 2024-09-19
- Fornecedor: Alibaba
