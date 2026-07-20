---
title: "Flan-T5 XL: Complete Benchmark Performance Guide"
description: "In-depth analysis of Flan-T5 XL performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2022-12-07
lastmod: 2022-12-07
draft: false
weight: 10
model_id: "flan-t5-xl"
vendor: "other"
version: "flan-t5-xl"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Flan-T5 XL

## Aperçu du modèle

Google Flan-T5 XL 3B 指令微调模型, 4K 上下文, 基于多任务指令微调, 适合零样本泛化任务。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | flan-t5-xl | 2022-12-07 | 4K | text | text | Apache 2.0 |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 60.4 | % | 5-shot |
| HumanEval | 34.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 46.5 | % | 0-shot CoT |
| MATH | 27.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 52.5 | % | 3-shot CoT |
| GPQA | 22.6 | % | 0-shot |
| IFEval | 55.7 | % | prompt_strict |
| ARC | 88.0 | % | challenge |
| MUSR | 40.2 | % | 0-shot |
| WinoGrande | 75.5 | % | 0-shot |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- 可靠的通用模型。

## Faiblesses

- HumanEval 34.0，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Cas d'usage

- 通用对话与问答

## Références

- [Flan-T5 XL Documentation](https://huggingface.co/models)
- Date de sortie: 2022-12-07
- Fournisseur: Other
