---
title: "Mistral Small: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Small performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-26
lastmod: 2024-02-26
draft: false
weight: 10
model_id: "mistral-small"
vendor: "mistral"
version: "small"
tags: ["realtime"]
---

# Mistral Small

## Aperçu du modèle

Mistral AI Small 经济型模型, 32K 上下文, 速度快成本低, 适合高吞吐量实时场景。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | small | 2024-02-26 | 32K | text | text | Apache 2.0 |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.2 | % | 5-shot |
| HumanEval | 74.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.7 | % | 0-shot CoT |
| MATH | 45.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.6 | % | 3-shot CoT |
| GPQA | 43.7 | % | 0-shot |
| IFEval | 74.0 | % | prompt_strict |
| ARC | 91.2 | % | challenge |
| MUSR | 49.3 | % | 0-shot |
| WinoGrande | 78.2 | % | 0-shot |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- MMLU score 81.2, strong knowledge reasoning.

## Faiblesses

- 闭源专有模型，不支持自托管。

## Cas d'usage

- 代码生成与调试

## Références

- [Mistral Small Documentation](https://docs.mistral.ai/)
- Date de sortie: 2024-02-26
- Fournisseur: Mistral
