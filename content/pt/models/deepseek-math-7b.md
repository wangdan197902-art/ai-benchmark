---
title: "DeepSeek Math 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek Math 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-06
lastmod: 2024-02-06
draft: false
weight: 10
model_id: "deepseek-math-7b"
vendor: "deepseek"
version: "math-7b"
tags: ["open-weights", "math", "self-hostable"]
---

# DeepSeek Math 7B

## Visão geral do modelo

DeepSeek Math 7B 数学专用开源模型, 4K 上下文, 在 MATH 基准上达到 64.7%, 7B 规模数学模型领先。

## Especificações principais

| Fornecedor | Versão | Data de lançamento | Janela de contexto | Modalidades de entrada | Modalidades de saída | Licença |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | math-7b | 2024-02-06 | 4K | text | text | DeepSeek License |

## Desempenho em benchmarks

| Benchmark | Pontuação | Unidade | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.3 | % | 5-shot |
| HumanEval | 54.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.1 | % | 0-shot CoT |
| MATH | 53.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.9 | % | 3-shot CoT |
| GPQA | 40.5 | % | 0-shot |
| IFEval | 61.1 | % | prompt_strict |
| ARC | 90.5 | % | challenge |
| MUSR | 49.8 | % | 0-shot |
| WinoGrande | 79.2 | % | 0-shot |

## Preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*por milhão de tokens*

## Pontos fortes

- 可靠的通用模型。

## Pontos fracos

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Casos de uso

- 通用对话与问答

## Referências

- [DeepSeek Math 7B Documentação](https://api-docs.deepseek.com/)
- Data de lançamento: 2024-02-06
- Fornecedor: Deepseek
