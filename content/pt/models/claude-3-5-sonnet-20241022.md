---
title: "Claude 3.5 Sonnet (2024-10-22): Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3.5 Sonnet (2024-10-22) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-22
lastmod: 2024-10-22
draft: false
weight: 10
model_id: "claude-3-5-sonnet-20241022"
vendor: "anthropic"
version: "3.5-sonnet-20241022"
tags: ["flagship", "coding", "long-context"]
---

# Claude 3.5 Sonnet (2024-10-22)

## Visão geral do modelo

Anthropic Claude 3.5 Sonnet 2024-10-22 版本, 引入计算机使用能力, 编码与推理性能再次提升。

## Especificações principais

| Fornecedor | Versão | Data de lançamento | Janela de contexto | Modalidades de entrada | Modalidades de saída | Licença |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3.5-sonnet-20241022 | 2024-10-22 | 200K | text, image | text | Proprietary |

## Desempenho em benchmarks

| Benchmark | Pontuação | Unidade | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 87.2 | % | 5-shot |
| HumanEval | 86.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 94.0 | % | 0-shot CoT |
| MATH | 75.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 84.2 | % | 3-shot CoT |
| GPQA | 50.9 | % | 0-shot |
| IFEval | 81.6 | % | prompt_strict |
| ARC | 96.8 | % | challenge |
| MUSR | 71.8 | % | 0-shot |
| WinoGrande | 86.9 | % | 0-shot |

## Preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*por milhão de tokens*

## Pontos fortes

- MMLU score 87.2, strong knowledge reasoning.
- HumanEval 86.1, excellent code generation.
- GSM8K 94.0, robust math reasoning.
- 上下文窗口 200K，支持长文本。

## Pontos fracos

- 闭源专有模型，不支持自托管。

## Casos de uso

- 代码生成与调试
- 长文档摘要
- Agent 工作流与工具调用

## Referências

- [Claude 3.5 Sonnet (2024-10-22) Documentação](https://docs.anthropic.com/claude/docs)
- Data de lançamento: 2024-10-22
- Fornecedor: Anthropic
