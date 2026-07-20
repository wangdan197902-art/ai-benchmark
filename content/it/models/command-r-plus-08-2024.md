---
title: "Command R+ (08-2024): Complete Benchmark Performance Guide"
description: "In-depth analysis of Command R+ (08-2024) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "command-r-plus-08-2024"
vendor: "cohere"
version: "r-plus-08-2024"
tags: ["rag", "enterprise", "tool-use"]
---

# Command R+ (08-2024)

## Panoramica del modello

Cohere Command R+ 08-2024 版本, 128K 上下文, 改进代码生成与多语言能力, 性能接近 GPT-4。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | r-plus-08-2024 | 2024-08-13 | 128K | text | text | CC-BY-NC-4.0 |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.3 | % | 5-shot |
| HumanEval | 75.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 80.8 | % | 0-shot CoT |
| MATH | 43.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.1 | % | 3-shot CoT |
| GPQA | 38.7 | % | 0-shot |
| IFEval | 72.1 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 51.1 | % | 0-shot |
| WinoGrande | 83.4 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- MMLU score 82.3, strong knowledge reasoning.
- 企业级合规认证。

## Punti deboli

- 闭源专有模型，不支持自托管。

## Casi d'uso

- 代码生成与调试
- 企业客户支持

## Riferimenti

- [Command R+ (08-2024) Documentazione](https://docs.cohere.com/docs)
- Data di rilascio: 2024-08-13
- Fornitore: Cohere
