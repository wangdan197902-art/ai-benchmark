---
title: "Command R+: Complete Benchmark Performance Guide"
description: "In-depth analysis of Command R+ performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-04
lastmod: 2024-04-04
draft: false
weight: 10
model_id: "command-r-plus"
vendor: "cohere"
version: "r-plus"
tags: ["rag", "enterprise", "tool-use"]
---

# Command R+

## Visão geral do modelo

Cohere Command R+ 是面向企业的 104B 参数模型，128K 上下文窗口，针对检索增强生成（RAG）与工具调用优化，支持 SOC2/GDPR/ISO 27001 合规，适合企业级生产部署。

## Especificações principais

| Fornecedor | Versão | Data de lançamento | Janela de contexto | Modalidades de entrada | Modalidades de saída | Licença |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | r-plus | 2024-04-04 | 128K | text | text | CC-BY-NC-4.0 |

## Desempenho em benchmarks

| Benchmark | Pontuação | Unidade | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.0 | % | 5-shot |
| HumanEval | 70.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 68.4 | % | 0-shot CoT |
| MATH | 35.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.1 | % | 3-shot CoT |

## Preços

| Entrada | Saída | Leitura de cache | Escrita de cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*por milhão de tokens*

## Pontos fortes

- 企业级合规认证。

## Pontos fracos

- 闭源专有模型，不支持自托管。

## Casos de uso

- 代码生成与调试
- 企业客户支持

## Referências

- [Command R+ Documentação](https://docs.cohere.com/docs/command-r-plus)
- Data de lançamento: 2024-04-04
- Fornecedor: Cohere
