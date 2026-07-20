---
title: "Command R: Complete Benchmark Performance Guide"
description: "In-depth analysis of Command R performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-11
lastmod: 2024-03-11
draft: false
weight: 10
model_id: "command-r"
vendor: "cohere"
version: "r"
tags: ["rag", "enterprise", "tool-use"]
---

# Command R

## Modellöversikt

Cohere Command R 经济型 35B 模型, 128K 上下文, 针对 RAG 与工具调用优化, 适合大规模部署。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | r | 2024-03-11 | 128K | text | text | CC-BY-NC-4.0 |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.3 | % | 5-shot |
| HumanEval | 75.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 86.9 | % | 0-shot CoT |
| MATH | 43.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.4 | % | 3-shot CoT |
| GPQA | 44.0 | % | 0-shot |
| IFEval | 74.1 | % | prompt_strict |
| ARC | 93.9 | % | challenge |
| MUSR | 57.0 | % | 0-shot |
| WinoGrande | 84.8 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- GSM8K 86.9, robust math reasoning.
- 企业级合规认证。

## Svagheter

- 闭源专有模型，不支持自托管。

## Användningsområden

- 代码生成与调试
- 企业客户支持

## Referenser

- [Command R Dokumentation](https://docs.cohere.com/docs)
- Releasedatum: 2024-03-11
- Leverantör: Cohere
