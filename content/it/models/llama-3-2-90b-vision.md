---
title: "Llama 3.2 90B Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.2 90B Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-25
lastmod: 2024-09-25
draft: false
weight: 10
model_id: "llama-3-2-90b-vision"
vendor: "meta"
version: "3.2-90b-vision"
tags: ["open-weights", "multimodal", "self-hostable"]
---

# Llama 3.2 90B Vision

## Panoramica del modello

Meta Llama 3.2 90B Vision 多模态开源模型, 128K 上下文, 支持图像理解, 性能接近 GPT-4V。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.2-90b-vision | 2024-09-25 | 128K | text, image | text | Llama 3.2 Community License |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.5 | % | 5-shot |
| HumanEval | 73.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.6 | % | 0-shot CoT |
| MATH | 52.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.1 | % | 3-shot CoT |
| GPQA | 42.2 | % | 0-shot |
| IFEval | 74.5 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 53.5 | % | 0-shot |
| WinoGrande | 79.3 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 支持文本、图像、音频多模态输入。

## Punti deboli

- 闭源专有模型，不支持自托管。

## Casi d'uso

- 代码生成与调试
- 视觉与图像理解

## Riferimenti

- [Llama 3.2 90B Vision Documentazione](https://llama.meta.com/docs/)
- Data di rilascio: 2024-09-25
- Fornitore: Meta
