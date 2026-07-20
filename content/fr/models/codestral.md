---
title: "Codestral: Complete Benchmark Performance Guide"
description: "In-depth analysis of Codestral performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-29
lastmod: 2024-05-29
draft: false
weight: 10
model_id: "codestral"
vendor: "mistral"
version: "codestral"
tags: ["coding", "open-weights"]
---

# Codestral

## Aperçu du modèle

Mistral Codestral 22B 代码专用模型, 32K 上下文, 支持 80+ 编程语言, 代码生成与补全性能突出。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | codestral | 2024-05-29 | 32K | text | text | MNPL |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.1 | % | 5-shot |
| HumanEval | 69.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.3 | % | 0-shot CoT |
| MATH | 29.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 58.3 | % | 3-shot CoT |
| GPQA | 32.4 | % | 0-shot |
| IFEval | 59.4 | % | prompt_strict |
| ARC | 87.4 | % | challenge |
| MUSR | 47.2 | % | 0-shot |
| WinoGrande | 75.8 | % | 0-shot |

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

- [Codestral Documentation](https://docs.mistral.ai/)
- Date de sortie: 2024-05-29
- Fournisseur: Mistral
