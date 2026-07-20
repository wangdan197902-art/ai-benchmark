---
title: "Microsoft WizardLM 2 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Microsoft WizardLM 2 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-15
lastmod: 2024-04-15
draft: false
weight: 10
model_id: "microsoft-wizardlm-2-7b"
vendor: "other"
version: "wizardlm-2-7b"
tags: ["open-weights", "self-hostable"]
---

# Microsoft WizardLM 2 7B

## Panoramica del modello

Microsoft WizardLM 2 7B 经济型微调模型, 32K 上下文, 基于 Llama 3 7B, 改进指令遵循能力。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardlm-2-7b | 2024-04-15 | 32K | text | text | Llama 3 Community License |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.7 | % | 5-shot |
| HumanEval | 68.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 58.5 | % | 0-shot CoT |
| MATH | 30.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 69.4 | % | 3-shot CoT |
| GPQA | 26.1 | % | 0-shot |
| IFEval | 56.9 | % | prompt_strict |
| ARC | 85.6 | % | challenge |
| MUSR | 49.3 | % | 0-shot |
| WinoGrande | 76.8 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 可靠的通用模型。

## Punti deboli

- 闭源专有模型，不支持自托管。

## Casi d'uso

- 通用对话与问答

## Riferimenti

- [Microsoft WizardLM 2 7B Documentazione](https://huggingface.co/models)
- Data di rilascio: 2024-04-15
- Fornitore: Other
