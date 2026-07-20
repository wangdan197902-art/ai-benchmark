---
title: "Mistral Small 3: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Small 3 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2025-01-29
lastmod: 2025-01-29
draft: false
weight: 10
model_id: "mistral-small-3"
vendor: "mistral"
version: "small-3"
tags: ["open-weights", "self-hostable"]
---

# Mistral Small 3

## Aperçu du modèle

Mistral Small 3 开源模型, 24B 参数, 32K 上下文, 性能接近 Mistral Large 2, Apache 2.0 可商用。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | small-3 | 2025-01-29 | 32K | text | text | Apache 2.0 |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.9 | % | 5-shot |
| HumanEval | 74.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.6 | % | 0-shot CoT |
| MATH | 39.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.3 | % | 3-shot CoT |
| GPQA | 30.1 | % | 0-shot |
| IFEval | 76.9 | % | prompt_strict |
| ARC | 91.8 | % | challenge |
| MUSR | 46.0 | % | 0-shot |
| WinoGrande | 78.8 | % | 0-shot |

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

- 代码生成与调试

## Références

- [Mistral Small 3 Documentation](https://docs.mistral.ai/)
- Date de sortie: 2025-01-29
- Fournisseur: Mistral
