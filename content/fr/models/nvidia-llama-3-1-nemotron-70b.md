---
title: "NVIDIA Llama 3.1 Nemotron 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of NVIDIA Llama 3.1 Nemotron 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-17
lastmod: 2024-10-17
draft: false
weight: 10
model_id: "nvidia-llama-3-1-nemotron-70b"
vendor: "other"
version: "nvidia-llama-3-1-nemotron-70b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# NVIDIA Llama 3.1 Nemotron 70B

## Aperçu du modèle

NVIDIA Llama 3.1 Nemotron 70B, 131K 上下文, NVIDIA 优化 Llama 3.1, 在 Arena 上接近 GPT-4o。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nvidia-llama-3-1-nemotron-70b | 2024-10-17 | 131K | text | text | Llama 3.1 Community License |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.4 | % | 5-shot |
| HumanEval | 66.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.8 | % | 0-shot CoT |
| MATH | 40.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.6 | % | 3-shot CoT |
| GPQA | 37.6 | % | 0-shot |
| IFEval | 69.6 | % | prompt_strict |
| ARC | 93.2 | % | challenge |
| MUSR | 47.7 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- MMLU score 80.4, strong knowledge reasoning.

## Faiblesses

- 闭源专有模型，不支持自托管。

## Cas d'usage

- 通用对话与问答

## Références

- [NVIDIA Llama 3.1 Nemotron 70B Documentation](https://huggingface.co/models)
- Date de sortie: 2024-10-17
- Fournisseur: Other
