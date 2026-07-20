---
title: "Phi-1.5: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-1.5 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-14
lastmod: 2023-09-14
draft: false
weight: 10
model_id: "phi-1-5"
vendor: "other"
version: "phi-1-5"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Phi-1.5

## Panoramica del modello

Microsoft Phi-1.5 1.3B 模型, 2K 上下文, 改进推理能力, 在 1.3B 规模上接近 7B 模型水平。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-1-5 | 2023-09-14 | 2K | text | text | MIT |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.4 | % | 5-shot |
| HumanEval | 39.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 34.2 | % | 0-shot CoT |
| MATH | 27.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 49.5 | % | 3-shot CoT |
| GPQA | 16.9 | % | 0-shot |
| IFEval | 48.0 | % | prompt_strict |
| ARC | 75.9 | % | challenge |
| MUSR | 30.3 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 可靠的通用模型。

## Punti deboli

- MMLU 仅 58.4，知识推理偏弱。
- HumanEval 39.2，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## Casi d'uso

- 通用对话与问答

## Riferimenti

- [Phi-1.5 Documentazione](https://huggingface.co/models)
- Data di rilascio: 2023-09-14
- Fornitore: Other
