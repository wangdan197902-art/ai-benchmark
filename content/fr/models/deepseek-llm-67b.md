---
title: "DeepSeek LLM 67B: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek LLM 67B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-05
lastmod: 2024-01-05
draft: false
weight: 10
model_id: "deepseek-llm-67b"
vendor: "deepseek"
version: "llm-67b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# DeepSeek LLM 67B

## Aperçu du modèle

DeepSeek LLM 67B 通用开源模型, 32K 上下文, 中英文能力平衡, 在开源 67B 模型中表现突出。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | llm-67b | 2024-01-05 | 32K | text | text | DeepSeek License |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.2 | % | 5-shot |
| HumanEval | 68.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.9 | % | 0-shot CoT |
| MATH | 39.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.6 | % | 3-shot CoT |
| GPQA | 37.3 | % | 0-shot |
| IFEval | 76.8 | % | prompt_strict |
| ARC | 94.0 | % | challenge |
| MUSR | 51.9 | % | 0-shot |
| WinoGrande | 78.1 | % | 0-shot |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- 可靠的通用模型。

## Faiblesses

- 闭源专有模型，不支持自托管。

## Cas d'usage

- 通用对话与问答

## Références

- [DeepSeek LLM 67B Documentation](https://api-docs.deepseek.com/)
- Date de sortie: 2024-01-05
- Fournisseur: Deepseek
