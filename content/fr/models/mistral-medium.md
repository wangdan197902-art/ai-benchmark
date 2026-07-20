---
title: "Mistral Medium: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Medium performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-11
lastmod: 2023-12-11
draft: false
weight: 10
model_id: "mistral-medium"
vendor: "mistral"
version: "medium"
tags: ["eu-residency"]
---

# Mistral Medium

## Aperçu du modèle

Mistral AI Medium 中端模型, 32K 上下文, 平衡性能与成本, 适合企业级通用任务。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | medium | 2023-12-11 | 32K | text | text | Apache 2.0 |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.9 | % | 5-shot |
| HumanEval | 78.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.5 | % | 0-shot CoT |
| MATH | 54.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.4 | % | 3-shot CoT |
| GPQA | 48.7 | % | 0-shot |
| IFEval | 77.4 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 64.3 | % | 0-shot |
| WinoGrande | 82.4 | % | 0-shot |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- MMLU score 82.9, strong knowledge reasoning.

## Faiblesses

- 闭源专有模型，不支持自托管。

## Cas d'usage

- 代码生成与调试

## Références

- [Mistral Medium Documentation](https://docs.mistral.ai/)
- Date de sortie: 2023-12-11
- Fournisseur: Mistral
