---
title: "OLMo 7B Instruct: Complete Benchmark Performance Guide"
description: "In-depth analysis of OLMo 7B Instruct performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-01
lastmod: 2024-02-01
draft: false
weight: 10
model_id: "olmo-7b-instruct"
vendor: "other"
version: "olmo-7b-instruct"
tags: ["open-weights", "self-hostable"]
---

# OLMo 7B Instruct

## Panoramica del modello

AllenAI OLMo 7B Instruct 指令微调版本, 2K 上下文, 改进指令遵循能力, 适合对话与助手场景。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | olmo-7b-instruct | 2024-02-01 | 2K | text | text | Apache 2.0 |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.6 | % | 5-shot |
| HumanEval | 50.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 58.7 | % | 0-shot CoT |
| MATH | 34.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.5 | % | 3-shot CoT |
| GPQA | 30.5 | % | 0-shot |
| IFEval | 63.6 | % | prompt_strict |
| ARC | 88.0 | % | challenge |
| MUSR | 42.5 | % | 0-shot |
| WinoGrande | 78.9 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 可靠的通用模型。

## Punti deboli

- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## Casi d'uso

- 通用对话与问答

## Riferimenti

- [OLMo 7B Instruct Documentazione](https://huggingface.co/models)
- Data di rilascio: 2024-02-01
- Fornitore: Other
