---
title: "Codestral Mamba: Complete Benchmark Performance Guide"
description: "In-depth analysis of Codestral Mamba performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-16
lastmod: 2024-07-16
draft: false
weight: 10
model_id: "codestral-mamba"
vendor: "mistral"
version: "codestral-mamba"
tags: ["coding", "open-weights", "long-context"]
---

# Codestral Mamba

## Panoramica del modello

Mistral Codestral Mamba 7B 代码模型, 256K 上下文, 基于 Mamba 架构, 线性时间复杂度适合长序列。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | codestral-mamba | 2024-07-16 | 256K | text | text | Apache 2.0 |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 59.3 | % | 5-shot |
| HumanEval | 86.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 67.8 | % | 0-shot CoT |
| MATH | 28.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.0 | % | 3-shot CoT |
| GPQA | 36.3 | % | 0-shot |
| IFEval | 65.5 | % | prompt_strict |
| ARC | 87.4 | % | challenge |
| MUSR | 47.0 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- HumanEval 86.2, excellent code generation.
- 上下文窗口 256K，支持长文本。

## Punti deboli

- MMLU 仅 59.3，知识推理偏弱。
- 闭源专有模型，不支持自托管。

## Casi d'uso

- 代码生成与调试
- 长文档摘要

## Riferimenti

- [Codestral Mamba Documentazione](https://docs.mistral.ai/)
- Data di rilascio: 2024-07-16
- Fornitore: Mistral
