---
title: "Microsoft WizardLM 2 8x22B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Microsoft WizardLM 2 8x22B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-15
lastmod: 2024-04-15
draft: false
weight: 10
model_id: "microsoft-wizardlm-2-8x22b"
vendor: "other"
version: "wizardlm-2-8x22b"
tags: ["open-weights", "moe", "self-hostable"]
---

# Microsoft WizardLM 2 8x22B

## Aperçu du modèle

Microsoft WizardLM 2 8x22B 微调模型, 64K 上下文, 基于 Mixtral 8x22B, 在 Arena 上接近 GPT-4。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardlm-2-8x22b | 2024-04-15 | 65K | text | text | Apache 2.0 |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.9 | % | 5-shot |
| HumanEval | 77.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.7 | % | 0-shot CoT |
| MATH | 39.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 73.6 | % | 3-shot CoT |
| GPQA | 39.3 | % | 0-shot |
| IFEval | 75.3 | % | prompt_strict |
| ARC | 92.1 | % | challenge |
| MUSR | 58.0 | % | 0-shot |
| WinoGrande | 81.6 | % | 0-shot |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- 采用 MoE 混合专家架构。

## Faiblesses

- 闭源专有模型，不支持自托管。

## Cas d'usage

- 代码生成与调试

## Références

- [Microsoft WizardLM 2 8x22B Documentation](https://huggingface.co/models)
- Date de sortie: 2024-04-15
- Fournisseur: Other
