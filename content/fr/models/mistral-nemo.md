---
title: "Mistral Nemo: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Nemo performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-18
lastmod: 2024-07-18
draft: false
weight: 10
model_id: "mistral-nemo"
vendor: "mistral"
version: "nemo"
tags: ["open-weights", "self-hostable", "long-context"]
---

# Mistral Nemo

## Aperçu du modèle

Mistral Nemo 12B 开源模型, 128K 上下文, 与 NVIDIA 合作开发, 适合本地部署与多语言任务。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | nemo | 2024-07-18 | 128K | text | text | Apache 2.0 |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.2 | % | 5-shot |
| HumanEval | 69.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 70.0 | % | 0-shot CoT |
| MATH | 43.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.2 | % | 3-shot CoT |
| GPQA | 36.1 | % | 0-shot |
| IFEval | 56.0 | % | prompt_strict |
| ARC | 90.5 | % | challenge |
| MUSR | 38.5 | % | 0-shot |
| WinoGrande | 73.2 | % | 0-shot |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- 上下文窗口 128K，支持长文本。

## Faiblesses

- 闭源专有模型，不支持自托管。

## Cas d'usage

- 长文档摘要

## Références

- [Mistral Nemo Documentation](https://docs.mistral.ai/)
- Date de sortie: 2024-07-18
- Fournisseur: Mistral
