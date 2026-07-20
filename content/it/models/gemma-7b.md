---
title: "Gemma 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemma 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-21
lastmod: 2024-02-21
draft: false
weight: 10
model_id: "gemma-7b"
vendor: "google"
version: "gemma-7b"
tags: ["open-weights", "self-hostable"]
---

# Gemma 7B

## Panoramica del modello

Google Gemma 7B 开源模型, 8K 上下文, 基于 Gemini 技术, 在 7B 规模上达到 Llama 2 13B 性能。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | gemma-7b | 2024-02-21 | 8K | text | text | Gemma License |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.6 | % | 5-shot |
| HumanEval | 61.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.6 | % | 0-shot CoT |
| MATH | 25.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.7 | % | 3-shot CoT |
| GPQA | 37.1 | % | 0-shot |
| IFEval | 66.9 | % | prompt_strict |
| ARC | 88.4 | % | challenge |
| MUSR | 36.2 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 可靠的通用模型。

## Punti deboli

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Casi d'uso

- 通用对话与问答

## Riferimenti

- [Gemma 7B Documentazione](https://ai.google.dev/gemma/docs)
- Data di rilascio: 2024-02-21
- Fornitore: Google
