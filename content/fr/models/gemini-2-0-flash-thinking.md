---
title: "Gemini 2.0 Flash Thinking: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 2.0 Flash Thinking performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-12-19
lastmod: 2024-12-19
draft: false
weight: 10
model_id: "gemini-2-0-flash-thinking"
vendor: "google"
version: "2.0-flash-thinking"
tags: ["flagship", "reasoning", "multimodal"]
---

# Gemini 2.0 Flash Thinking

## Aperçu du modèle

Google Gemini 2.0 Flash Thinking 实验版, 1M 上下文, 链式思维推理, 在数学与编码上接近 o1。

## Spécifications principales

| Fournisseur | Version | Date de sortie | Fenêtre de contexte | Modalités d'entrée | Modalités de sortie | Licence |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 2.0-flash-thinking | 2024-12-19 | 1048K | text, image | text | Proprietary |

## Performance aux benchmarks

| Benchmark | Score | Unité | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 86.5 | % | 5-shot |
| HumanEval | 87.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 91.3 | % | 0-shot CoT |
| MATH | 56.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 87.9 | % | 3-shot CoT |
| GPQA | 61.0 | % | 0-shot |
| IFEval | 82.8 | % | prompt_strict |
| ARC | 95.0 | % | challenge |
| MUSR | 70.8 | % | 0-shot |
| WinoGrande | 88.1 | % | 0-shot |

## Tarification

| Entrée | Sortie | Lecture cache | Écriture cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*par million de jetons*

## Forces

- MMLU score 86.5, strong knowledge reasoning.
- HumanEval 87.2, excellent code generation.
- GSM8K 91.3, robust math reasoning.
- 支持文本、图像、音频多模态输入。

## Faiblesses

- 闭源专有模型，不支持自托管。

## Cas d'usage

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## Références

- [Gemini 2.0 Flash Thinking Documentation](https://ai.google.dev/gemini-api/docs)
- Date de sortie: 2024-12-19
- Fournisseur: Google
