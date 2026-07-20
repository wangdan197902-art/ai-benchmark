---
title: "Phi-4: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-4 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-12-12
lastmod: 2024-12-12
draft: false
weight: 10
model_id: "phi-4"
vendor: "other"
version: "phi-4"
tags: ["open-weights", "self-hostable", "reasoning"]
---

# Phi-4

## Aperçu du modèle

Microsoft Phi-4 14B 模型, 16K 上下文, 改进推理与数学能力, 在 14B 规模上接近 GPT-4o-mini。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-4 | 2024-12-12 | 16K | text | text | MIT |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.2 | % | 5-shot |
| HumanEval | 62.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 71.1 | % | 0-shot CoT |
| MATH | 39.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.9 | % | 3-shot CoT |
| GPQA | 30.1 | % | 0-shot |
| IFEval | 59.6 | % | prompt_strict |
| ARC | 85.1 | % | challenge |
| MUSR | 38.6 | % | 0-shot |
| WinoGrande | 78.3 | % | 0-shot |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- 可靠的通用模型。

## Faiblesses

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Cas d'usage

- 通用对话与问答

## Références

- [Phi-4 Documentation](https://huggingface.co/models)
- Date de sortie: 2024-12-12
- Fournisseur: Other
