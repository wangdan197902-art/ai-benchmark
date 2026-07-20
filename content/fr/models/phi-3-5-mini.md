---
title: "Phi-3.5 Mini: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3.5 Mini performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-16
lastmod: 2024-08-16
draft: false
weight: 10
model_id: "phi-3-5-mini"
vendor: "other"
version: "phi-3-5-mini"
tags: ["open-weights", "self-hostable", "long-context"]
---

# Phi-3.5 Mini

## Aperçu du modèle

Microsoft Phi-3.5 Mini 3.8B 模型, 128K 上下文, 改进多语言与长上下文能力, 适合边缘部署。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-5-mini | 2024-08-16 | 128K | text | text | MIT |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 55.7 | % | 5-shot |
| HumanEval | 44.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 22.1 | % | 0-shot CoT |
| MATH | 9.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 47.5 | % | 3-shot CoT |
| GPQA | 24.4 | % | 0-shot |
| IFEval | 48.7 | % | prompt_strict |
| ARC | 81.5 | % | challenge |
| MUSR | 31.2 | % | 0-shot |
| WinoGrande | 68.6 | % | 0-shot |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- 上下文窗口 128K，支持长文本。

## Faiblesses

- MMLU 仅 55.7，知识推理偏弱。
- HumanEval 44.0，代码能力较弱。
- 闭源专有模型，不支持自托管。

## Cas d'usage

- 长文档摘要

## Références

- [Phi-3.5 Mini Documentation](https://huggingface.co/models)
- Date de sortie: 2024-08-16
- Fournisseur: Other
