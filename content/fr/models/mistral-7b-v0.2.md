---
title: "Mistral 7B v0.2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral 7B v0.2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-23
lastmod: 2024-03-23
draft: false
weight: 10
model_id: "mistral-7b-v0.2"
vendor: "mistral"
version: "7b-v0.2"
tags: ["open-weights", "self-hostable"]
---

# Mistral 7B v0.2

## Aperçu du modèle

Mistral 7B v0.2 开源模型, 32K 上下文, 扩展上下文窗口, 改进推理, 适合通用任务。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 7b-v0.2 | 2024-03-23 | 32K | text | text | Apache 2.0 |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.4 | % | 5-shot |
| HumanEval | 59.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 56.2 | % | 0-shot CoT |
| MATH | 25.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.3 | % | 3-shot CoT |
| GPQA | 33.9 | % | 0-shot |
| IFEval | 59.2 | % | prompt_strict |
| ARC | 85.5 | % | challenge |
| MUSR | 36.7 | % | 0-shot |
| WinoGrande | 71.7 | % | 0-shot |

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

- [Mistral 7B v0.2 Documentation](https://docs.mistral.ai/)
- Date de sortie: 2024-03-23
- Fournisseur: Mistral
