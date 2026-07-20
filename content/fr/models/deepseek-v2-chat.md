---
title: "DeepSeek V2 Chat: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek V2 Chat performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-17
lastmod: 2024-06-17
draft: false
weight: 10
model_id: "deepseek-v2-chat"
vendor: "deepseek"
version: "v2-chat"
tags: ["open-weights", "moe", "chinese"]
---

# DeepSeek V2 Chat

## Aperçu du modèle

DeepSeek V2 Chat 对话版本, 32K 上下文, 针对对话场景优化, 适合聊天助手与客服应用。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | v2-chat | 2024-06-17 | 32K | text | text | DeepSeek License |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.6 | % | 5-shot |
| HumanEval | 67.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.4 | % | 0-shot CoT |
| MATH | 49.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.4 | % | 3-shot CoT |
| GPQA | 38.3 | % | 0-shot |
| IFEval | 71.5 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 52.0 | % | 0-shot |
| WinoGrande | 80.2 | % | 0-shot |

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

- 通用对话与问答

## Références

- [DeepSeek V2 Chat Documentation](https://api-docs.deepseek.com/)
- Date de sortie: 2024-06-17
- Fournisseur: Deepseek
