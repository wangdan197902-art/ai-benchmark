---
title: "OLMo 1.7 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of OLMo 1.7 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-23
lastmod: 2024-08-23
draft: false
weight: 10
model_id: "olmo-1-7-7b"
vendor: "other"
version: "olmo-1-7-7b"
tags: ["open-weights", "self-hostable"]
---

# OLMo 1.7 7B

## Aperçu du modèle

AllenAI OLMo 1.7 7B 第二代模型, 4K 上下文, 改进训练流程, 性能超越初代 OLMo 7B。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | olmo-1-7-7b | 2024-08-23 | 4K | text | text | Apache 2.0 |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.5 | % | 5-shot |
| HumanEval | 67.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.5 | % | 0-shot CoT |
| MATH | 38.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 68.9 | % | 3-shot CoT |
| GPQA | 26.9 | % | 0-shot |
| IFEval | 61.2 | % | prompt_strict |
| ARC | 91.8 | % | challenge |
| MUSR | 42.6 | % | 0-shot |
| WinoGrande | 76.6 | % | 0-shot |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- 可靠的通用模型。

## Faiblesses

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Cas d'usage

- 通用对话与问答

## Références

- [OLMo 1.7 7B Documentation](https://huggingface.co/models)
- Date de sortie: 2024-08-23
- Fournisseur: Other
