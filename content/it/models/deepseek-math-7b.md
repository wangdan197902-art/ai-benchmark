---
title: "DeepSeek Math 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek Math 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-06
lastmod: 2024-02-06
draft: false
weight: 10
model_id: "deepseek-math-7b"
vendor: "deepseek"
version: "math-7b"
tags: ["open-weights", "math", "self-hostable"]
---

# DeepSeek Math 7B

## Panoramica del modello

DeepSeek Math 7B 数学专用开源模型, 4K 上下文, 在 MATH 基准上达到 64.7%, 7B 规模数学模型领先。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | math-7b | 2024-02-06 | 4K | text | text | DeepSeek License |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.3 | % | 5-shot |
| HumanEval | 54.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.1 | % | 0-shot CoT |
| MATH | 53.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.9 | % | 3-shot CoT |
| GPQA | 40.5 | % | 0-shot |
| IFEval | 61.1 | % | prompt_strict |
| ARC | 90.5 | % | challenge |
| MUSR | 49.8 | % | 0-shot |
| WinoGrande | 79.2 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 可靠的通用模型。

## Punti deboli

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Casi d'uso

- 通用对话与问答

## Riferimenti

- [DeepSeek Math 7B Documentazione](https://api-docs.deepseek.com/)
- Data di rilascio: 2024-02-06
- Fornitore: Deepseek
