---
title: "StableCode 3B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StableCode 3B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-19
lastmod: 2024-01-19
draft: false
weight: 10
model_id: "stablecode-3b"
vendor: "other"
version: "stablecode-3b"
tags: ["open-weights", "coding", "self-hostable", "long-context"]
---

# StableCode 3B

## Aperçu du modèle

Stability AI StableCode 3B 代码专用模型, 100K 上下文, 3B 参数, 支持多种编程语言代码补全。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | stablecode-3b | 2024-01-19 | 100K | text | text | Stability AI Community License |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.4 | % | 5-shot |
| HumanEval | 77.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 68.5 | % | 0-shot CoT |
| MATH | 31.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 58.4 | % | 3-shot CoT |
| GPQA | 24.5 | % | 0-shot |
| IFEval | 51.8 | % | prompt_strict |
| ARC | 86.4 | % | challenge |
| MUSR | 51.8 | % | 0-shot |
| WinoGrande | 70.9 | % | 0-shot |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- 上下文窗口 100K，支持长文本。

## Faiblesses

- 闭源专有模型，不支持自托管。

## Cas d'usage

- 代码生成与调试
- 长文档摘要

## Références

- [StableCode 3B Documentation](https://huggingface.co/models)
- Date de sortie: 2024-01-19
- Fournisseur: Other
