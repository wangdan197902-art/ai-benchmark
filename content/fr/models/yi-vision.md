---
title: "Yi Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of Yi Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
model_id: "yi-vision"
vendor: "other"
version: "yi-vision"
tags: ["multimodal", "chinese"]
---

# Yi Vision

## Aperçu du modèle

01.AI Yi Vision 多模态模型, 16K 上下文, 支持图像理解, 中英文视觉问答能力突出。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | yi-vision | 2024-05-13 | 16K | text, image | text | Proprietary |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 85.5 | % | 5-shot |
| HumanEval | 76.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 89.9 | % | 0-shot CoT |
| MATH | 58.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.3 | % | 3-shot CoT |
| GPQA | 50.3 | % | 0-shot |
| IFEval | 81.4 | % | prompt_strict |
| ARC | 95.1 | % | challenge |
| MUSR | 61.4 | % | 0-shot |
| WinoGrande | 82.3 | % | 0-shot |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- MMLU score 85.5, strong knowledge reasoning.
- GSM8K 89.9, robust math reasoning.
- 支持文本、图像、音频多模态输入。

## Faiblesses

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Cas d'usage

- 代码生成与调试
- 视觉与图像理解

## Références

- [Yi Vision Documentation](https://huggingface.co/models)
- Date de sortie: 2024-05-13
- Fournisseur: Other
