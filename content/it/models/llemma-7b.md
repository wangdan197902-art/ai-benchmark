---
title: "Llemma 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llemma 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-10-17
lastmod: 2023-10-17
draft: false
weight: 10
model_id: "llemma-7b"
vendor: "other"
version: "llemma-7b"
tags: ["open-weights", "math", "self-hostable"]
---

# Llemma 7B

## Panoramica del modello

TheBloke Llemma 7B 数学专用模型, 4K 上下文, 基于 Code Llama 7B 继续训练, 数学推理能力突出。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | llemma-7b | 2023-10-17 | 4K | text | text | Apache 2.0 |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 66.0 | % | 5-shot |
| HumanEval | 64.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.9 | % | 0-shot CoT |
| MATH | 47.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 73.1 | % | 3-shot CoT |
| GPQA | 37.4 | % | 0-shot |
| IFEval | 52.9 | % | prompt_strict |
| ARC | 87.4 | % | challenge |
| MUSR | 42.6 | % | 0-shot |
| WinoGrande | 70.8 | % | 0-shot |

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

- [Llemma 7B Documentazione](https://huggingface.co/models)
- Data di rilascio: 2023-10-17
- Fornitore: Other
