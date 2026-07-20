---
title: "Ministral 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Ministral 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-16
lastmod: 2024-10-16
draft: false
weight: 10
model_id: "ministral-8b"
vendor: "mistral"
version: "ministral-8b"
tags: ["open-weights", "self-hostable", "long-context"]
---

# Ministral 8B

## Panoramica del modello

Mistral Ministral 8B 边缘模型, 128K 上下文, 8B 参数, 为本地与边缘计算优化, 性能超越 Llama 3 8B。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | ministral-8b | 2024-10-16 | 128K | text | text | Mistral Research License |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.9 | % | 5-shot |
| HumanEval | 63.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.7 | % | 0-shot CoT |
| MATH | 39.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.0 | % | 3-shot CoT |
| GPQA | 35.1 | % | 0-shot |
| IFEval | 56.1 | % | prompt_strict |
| ARC | 85.5 | % | challenge |
| MUSR | 37.0 | % | 0-shot |
| WinoGrande | 75.3 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 上下文窗口 128K，支持长文本。

## Punti deboli

- 闭源专有模型，不支持自托管。

## Casi d'uso

- 长文档摘要

## Riferimenti

- [Ministral 8B Documentazione](https://docs.mistral.ai/)
- Data di rilascio: 2024-10-16
- Fornitore: Mistral
