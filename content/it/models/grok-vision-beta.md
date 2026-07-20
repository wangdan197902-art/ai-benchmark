---
title: "Grok Vision Beta: Complete Benchmark Performance Guide"
description: "In-depth analysis of Grok Vision Beta performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-04
lastmod: 2023-11-04
draft: false
weight: 10
model_id: "grok-vision-beta"
vendor: "xai"
version: "vision-beta"
tags: ["multimodal", "legacy"]
---

# Grok Vision Beta

## Panoramica del modello

xAI Grok Vision Beta 早期多模态预览版, 8K 上下文, 支持图像理解, 集成 X 平台实时信息。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Xai | vision-beta | 2023-11-04 | 8K | text, image | text | Proprietary |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 63.3 | % | 5-shot |
| HumanEval | 44.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 35.2 | % | 0-shot CoT |
| MATH | 24.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 56.8 | % | 3-shot CoT |
| GPQA | 32.4 | % | 0-shot |
| IFEval | 46.8 | % | prompt_strict |
| ARC | 88.2 | % | challenge |
| MUSR | 44.5 | % | 0-shot |
| WinoGrande | 67.5 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 支持文本、图像、音频多模态输入。

## Punti deboli

- HumanEval 44.0，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Casi d'uso

- 视觉与图像理解

## Riferimenti

- [Grok Vision Beta Documentazione](https://docs.x.ai/)
- Data di rilascio: 2023-11-04
- Fornitore: Xai
