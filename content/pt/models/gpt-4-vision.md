---
title: "GPT-4 Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-25
lastmod: 2024-01-25
draft: false
weight: 10
model_id: "gpt-4-vision"
vendor: "openai"
version: "4-vision"
tags: ["multimodal", "flagship"]
---

# GPT-4 Vision

## Visão geral do modelo

OpenAI GPT-4 Vision 正式版, 支持图像理解与多模态推理, 128K 上下文窗口。

## Especificações principais

| Fornecedor | Versão | Data de lançamento | Janela de contexto | Modalidades de entrada | Modalidades de saída | Licença |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-vision | 2024-01-25 | 128K | text, image | text | Proprietary |

## Desempenho em benchmarks

| Benchmark | Pontuação | Unidade | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.9 | % | 5-shot |
| HumanEval | 75.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.6 | % | 0-shot CoT |
| MATH | 48.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 80.9 | % | 3-shot CoT |
| GPQA | 41.8 | % | 0-shot |
| IFEval | 73.5 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 51.2 | % | 0-shot |
| WinoGrande | 86.9 | % | 0-shot |

## Preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*por milhão de tokens*

## Pontos fortes

- MMLU score 83.9, strong knowledge reasoning.
- 支持文本、图像、音频多模态输入。

## Pontos fracos

- 闭源专有模型，不支持自托管。

## Casos de uso

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## Referências

- [GPT-4 Vision Documentação](https://platform.openai.com/docs/models)
- Data de lançamento: 2024-01-25
- Fornecedor: Openai
