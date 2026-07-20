---
title: "Hermes 3 Llama 3.1 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Hermes 3 Llama 3.1 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "hermes-3-llama-3-1-70b"
vendor: "other"
version: "hermes-3-llama-3-1-70b"
tags: ["open-weights", "self-hostable"]
---

# Hermes 3 Llama 3.1 70B

## Aperçu du modèle

NousResearch Hermes 3 Llama 3.1 70B 微调模型, 131K 上下文, 改进指令遵循与中立性。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | hermes-3-llama-3-1-70b | 2024-08-12 | 131K | text | text | Llama 3.1 Community License |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.7 | % | 5-shot |
| HumanEval | 75.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 76.4 | % | 0-shot CoT |
| MATH | 54.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.9 | % | 3-shot CoT |
| GPQA | 30.1 | % | 0-shot |
| IFEval | 73.8 | % | prompt_strict |
| ARC | 91.4 | % | challenge |
| MUSR | 55.4 | % | 0-shot |
| WinoGrande | 83.9 | % | 0-shot |

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

- [Hermes 3 Llama 3.1 70B Documentation](https://huggingface.co/models)
- Date de sortie: 2024-08-12
- Fournisseur: Other
