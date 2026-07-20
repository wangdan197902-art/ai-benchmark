---
title: "GLM-4 Plus: Complete Benchmark Performance Guide"
description: "In-depth analysis of GLM-4 Plus performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "glm-4-plus"
vendor: "other"
version: "glm-4-plus"
tags: ["flagship", "chinese", "multimodal"]
---

# GLM-4 Plus

## Panoramica del modello

清华智谱 GLM-4 Plus 旗舰模型, 131K 上下文, 支持文本与图像输入, 中文能力突出。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | glm-4-plus | 2024-08-12 | 131K | text, image | text | Proprietary |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.3 | % | 5-shot |
| HumanEval | 72.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 81.8 | % | 0-shot CoT |
| MATH | 53.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.6 | % | 3-shot CoT |
| GPQA | 35.4 | % | 0-shot |
| IFEval | 79.2 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 51.3 | % | 0-shot |
| WinoGrande | 85.8 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- MMLU score 84.3, strong knowledge reasoning.
- 支持文本、图像、音频多模态输入。

## Punti deboli

- 闭源专有模型，不支持自托管。

## Casi d'uso

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## Riferimenti

- [GLM-4 Plus Documentazione](https://huggingface.co/models)
- Data di rilascio: 2024-08-12
- Fornitore: Other
