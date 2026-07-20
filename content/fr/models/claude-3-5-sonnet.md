---
title: "Claude 3.5 Sonnet: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3.5 Sonnet performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-20
lastmod: 2024-06-20
draft: false
weight: 10
model_id: "claude-3-5-sonnet"
vendor: "anthropic"
version: "3.5-sonnet"
tags: ["flagship", "coding", "long-context"]
---

# Claude 3.5 Sonnet

## Aperçu du modèle

Anthropic Claude 3.5 Sonnet 模型，200K 上下文窗口，在编码、视觉推理与长文本理解方面表现突出，平衡了智能与速度。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3.5-sonnet | 2024-06-20 | 200K | text, image | text | Proprietary |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 88.7 | % | 5-shot |
| HumanEval | 92.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 96.4 | % | 0-shot CoT |
| MATH | 71.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 84.5 | % | 3-shot CoT |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- MMLU score 88.7, strong knowledge reasoning.
- HumanEval 92.0, excellent code generation.
- GSM8K 96.4, robust math reasoning.
- 上下文窗口 200K，支持长文本。

## Faiblesses

- 闭源专有模型，不支持自托管。

## Cas d'usage

- 代码生成与调试
- 长文档摘要
- Agent 工作流与工具调用

## Références

- [Claude 3.5 Sonnet Documentation](https://docs.anthropic.com/claude/docs)
- Date de sortie: 2024-06-20
- Fournisseur: Anthropic
