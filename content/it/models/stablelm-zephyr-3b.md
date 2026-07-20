---
title: "StableLM Zephyr 3B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StableLM Zephyr 3B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-19
lastmod: 2024-01-19
draft: false
weight: 10
model_id: "stablelm-zephyr-3b"
vendor: "other"
version: "stablelm-zephyr-3b"
tags: ["open-weights", "self-hostable"]
---

# StableLM Zephyr 3B

## Panoramica del modello

Stability AI StableLM Zephyr 3B 对话微调模型, 4K 上下文, 基于 StableLM 2 1.6B DPO 微调。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | stablelm-zephyr-3b | 2024-01-19 | 4K | text | text | Stability AI Community License |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 44.3 | % | 5-shot |
| HumanEval | 47.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 36.2 | % | 0-shot CoT |
| MATH | 14.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 43.9 | % | 3-shot CoT |
| GPQA | 21.0 | % | 0-shot |
| IFEval | 55.3 | % | prompt_strict |
| ARC | 82.1 | % | challenge |
| MUSR | 23.5 | % | 0-shot |
| WinoGrande | 71.6 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 可靠的通用模型。

## Punti deboli

- MMLU 仅 44.3，知识推理偏弱。
- HumanEval 47.1，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Casi d'uso

- 通用对话与问答

## Riferimenti

- [StableLM Zephyr 3B Documentazione](https://huggingface.co/models)
- Data di rilascio: 2024-01-19
- Fornitore: Other
