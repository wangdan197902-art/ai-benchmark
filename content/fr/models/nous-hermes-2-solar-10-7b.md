---
title: "Nous Hermes 2 Solar 10.7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Nous Hermes 2 Solar 10.7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-19
lastmod: 2024-02-19
draft: false
weight: 10
model_id: "nous-hermes-2-solar-10-7b"
vendor: "other"
version: "nous-hermes-2-solar-10-7b"
tags: ["open-weights", "self-hostable"]
---

# Nous Hermes 2 Solar 10.7B

## Aperçu du modèle

NousResearch Hermes 2 Solar 10.7B 微调模型, 4K 上下文, 基于 Solar 10.7B, 性能接近 Llama 2 70B。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-hermes-2-solar-10-7b | 2024-02-19 | 4K | text | text | Apache 2.0 |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 63.4 | % | 5-shot |
| HumanEval | 59.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 59.6 | % | 0-shot CoT |
| MATH | 37.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.8 | % | 3-shot CoT |
| GPQA | 35.9 | % | 0-shot |
| IFEval | 55.6 | % | prompt_strict |
| ARC | 85.9 | % | challenge |
| MUSR | 39.6 | % | 0-shot |
| WinoGrande | 74.4 | % | 0-shot |

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

- [Nous Hermes 2 Solar 10.7B Documentation](https://huggingface.co/models)
- Date de sortie: 2024-02-19
- Fournisseur: Other
