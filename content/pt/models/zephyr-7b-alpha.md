---
title: "Zephyr 7B Alpha: Complete Benchmark Performance Guide"
description: "In-depth analysis of Zephyr 7B Alpha performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-10-04
lastmod: 2023-10-04
draft: false
weight: 10
model_id: "zephyr-7b-alpha"
vendor: "other"
version: "zephyr-7b-alpha"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Zephyr 7B Alpha

## Visão geral do modelo

HuggingFaceH4 Zephyr 7B Alpha 首版对话模型, 4K 上下文, 基于 Mistral 7B SFT 微调。

## Especificações principais

| Fornecedor | Versão | Data de lançamento | Janela de contexto | Modalidades de entrada | Modalidades de saída | Licença |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | zephyr-7b-alpha | 2023-10-04 | 4K | text | text | MIT |

## Desempenho em benchmarks

| Benchmark | Pontuação | Unidade | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 52.2 | % | 5-shot |
| HumanEval | 35.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 32.8 | % | 0-shot CoT |
| MATH | 23.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.7 | % | 3-shot CoT |
| GPQA | 34.3 | % | 0-shot |
| IFEval | 50.9 | % | prompt_strict |
| ARC | 84.7 | % | challenge |
| MUSR | 40.5 | % | 0-shot |
| WinoGrande | 75.0 | % | 0-shot |

## Preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*por milhão de tokens*

## Pontos fortes

- 可靠的通用模型。

## Pontos fracos

- MMLU 仅 52.2，知识推理偏弱。
- HumanEval 35.9，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Casos de uso

- 通用对话与问答

## Referências

- [Zephyr 7B Alpha Documentação](https://huggingface.co/models)
- Data de lançamento: 2023-10-04
- Fornecedor: Other
