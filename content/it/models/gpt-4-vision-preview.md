---
title: "GPT-4 Vision Preview: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 Vision Preview performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-25
lastmod: 2023-09-25
draft: false
weight: 10
model_id: "gpt-4-vision-preview"
vendor: "openai"
version: "4-vision-preview"
tags: ["multimodal", "flagship"]
---

# GPT-4 Vision Preview

## Panoramica del modello

OpenAI GPT-4 Vision 预览版, 支持图像输入理解, 128K 上下文, 多模态能力首次集成。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-vision-preview | 2023-09-25 | 128K | text, image | text | Proprietary |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 85.0 | % | 5-shot |
| HumanEval | 70.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.5 | % | 0-shot CoT |
| MATH | 49.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.0 | % | 3-shot CoT |
| GPQA | 36.3 | % | 0-shot |
| IFEval | 72.7 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 64.5 | % | 0-shot |
| WinoGrande | 80.6 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- MMLU score 85.0, strong knowledge reasoning.
- 支持文本、图像、音频多模态输入。

## Punti deboli

- 闭源专有模型，不支持自托管。

## Casi d'uso

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## Riferimenti

- [GPT-4 Vision Preview Documentazione](https://platform.openai.com/docs/models)
- Data di rilascio: 2023-09-25
- Fornitore: Openai
