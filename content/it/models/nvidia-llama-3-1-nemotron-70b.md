---
title: "NVIDIA Llama 3.1 Nemotron 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of NVIDIA Llama 3.1 Nemotron 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-17
lastmod: 2024-10-17
draft: false
weight: 10
model_id: "nvidia-llama-3-1-nemotron-70b"
vendor: "other"
version: "nvidia-llama-3-1-nemotron-70b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# NVIDIA Llama 3.1 Nemotron 70B

## Panoramica del modello

NVIDIA Llama 3.1 Nemotron 70B, 131K 上下文, NVIDIA 优化 Llama 3.1, 在 Arena 上接近 GPT-4o。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nvidia-llama-3-1-nemotron-70b | 2024-10-17 | 131K | text | text | Llama 3.1 Community License |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.4 | % | 5-shot |
| HumanEval | 66.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.8 | % | 0-shot CoT |
| MATH | 40.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.6 | % | 3-shot CoT |
| GPQA | 37.6 | % | 0-shot |
| IFEval | 69.6 | % | prompt_strict |
| ARC | 93.2 | % | challenge |
| MUSR | 47.7 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- MMLU score 80.4, strong knowledge reasoning.

## Punti deboli

- 闭源专有模型，不支持自托管。

## Casi d'uso

- 通用对话与问答

## Riferimenti

- [NVIDIA Llama 3.1 Nemotron 70B Documentazione](https://huggingface.co/models)
- Data di rilascio: 2024-10-17
- Fornitore: Other
