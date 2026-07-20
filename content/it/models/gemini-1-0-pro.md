---
title: "Gemini 1.0 Pro: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.0 Pro performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-06
lastmod: 2023-12-06
draft: false
weight: 10
model_id: "gemini-1-0-pro"
vendor: "google"
version: "1.0-pro"
tags: ["legacy"]
---

# Gemini 1.0 Pro

## Panoramica del modello

Google Gemini 1.0 Pro 首代模型, 32K 上下文, 在 MMLU/GSM8K 上超越 GPT-3.5, 多模态能力初步集成。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.0-pro | 2023-12-06 | 32K | text | text | Proprietary |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.5 | % | 5-shot |
| HumanEval | 76.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.4 | % | 0-shot CoT |
| MATH | 58.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.1 | % | 3-shot CoT |
| GPQA | 47.7 | % | 0-shot |
| IFEval | 75.1 | % | prompt_strict |
| ARC | 94.1 | % | challenge |
| MUSR | 57.8 | % | 0-shot |
| WinoGrande | 84.5 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- MMLU score 84.5, strong knowledge reasoning.

## Punti deboli

- 闭源专有模型，不支持自托管。

## Casi d'uso

- 代码生成与调试

## Riferimenti

- [Gemini 1.0 Pro Documentazione](https://ai.google.dev/gemini-api/docs)
- Data di rilascio: 2023-12-06
- Fornitore: Google
