---
title: "Mistral 7B v0.3: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral 7B v0.3 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-22
lastmod: 2024-05-22
draft: false
weight: 10
model_id: "mistral-7b-v0.3"
vendor: "mistral"
version: "7b-v0.3"
tags: ["open-weights", "self-hostable"]
---

# Mistral 7B v0.3

## Panoramica del modello

Mistral 7B v0.3 开源模型, 32K 上下文, 改进 v0.2, 扩展词汇表至 32768, 适合本地部署。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 7b-v0.3 | 2024-05-22 | 32K | text | text | Apache 2.0 |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 72.6 | % | 5-shot |
| HumanEval | 68.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 69.4 | % | 0-shot CoT |
| MATH | 26.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.5 | % | 3-shot CoT |
| GPQA | 31.2 | % | 0-shot |
| IFEval | 60.9 | % | prompt_strict |
| ARC | 88.9 | % | challenge |
| MUSR | 48.1 | % | 0-shot |
| WinoGrande | 72.7 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 可靠的通用模型。

## Punti deboli

- 闭源专有模型，不支持自托管。

## Casi d'uso

- 通用对话与问答

## Riferimenti

- [Mistral 7B v0.3 Documentazione](https://docs.mistral.ai/)
- Data di rilascio: 2024-05-22
- Fornitore: Mistral
