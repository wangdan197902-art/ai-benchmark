---
title: "WizardLM Team WizardLM 2 8x22B: Complete Benchmark Performance Guide"
description: "In-depth analysis of WizardLM Team WizardLM 2 8x22B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-15
lastmod: 2024-04-15
draft: false
weight: 10
model_id: "wizardlmteam-wizardlm-2-8x22b"
vendor: "other"
version: "wizardlmteam-wizardlm-2-8x22b"
tags: ["open-weights", "moe", "self-hostable"]
---

# WizardLM Team WizardLM 2 8x22B

## Panoramica del modello

WizardLM Team WizardLM 2 8x22B 官方发布版, 64K 上下文, 基于 Mixtral 8x22B 微调, Arena 上接近 GPT-4。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardlmteam-wizardlm-2-8x22b | 2024-04-15 | 65K | text | text | Apache 2.0 |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.2 | % | 5-shot |
| HumanEval | 70.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.9 | % | 0-shot CoT |
| MATH | 37.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 80.0 | % | 3-shot CoT |
| GPQA | 41.4 | % | 0-shot |
| IFEval | 70.7 | % | prompt_strict |
| ARC | 92.3 | % | challenge |
| MUSR | 56.8 | % | 0-shot |
| WinoGrande | 83.5 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 采用 MoE 混合专家架构。

## Punti deboli

- 闭源专有模型，不支持自托管。

## Casi d'uso

- 代码生成与调试

## Riferimenti

- [WizardLM Team WizardLM 2 8x22B Documentazione](https://huggingface.co/models)
- Data di rilascio: 2024-04-15
- Fornitore: Other
