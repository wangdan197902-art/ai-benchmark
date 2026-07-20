---
title: "DeepSeek Coder 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek Coder 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-25
lastmod: 2024-01-25
draft: false
weight: 10
model_id: "deepseek-coder-7b"
vendor: "deepseek"
version: "coder-7b"
tags: ["open-weights", "coding", "self-hostable"]
---

# DeepSeek Coder 7B

## Panoramica del modello

DeepSeek Coder 7B 代码专用开源模型, 16K 上下文, 7B 参数, 在 7B 规模上代码生成能力领先。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | coder-7b | 2024-01-25 | 16K | text | text | DeepSeek License |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 63.6 | % | 5-shot |
| HumanEval | 75.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 54.7 | % | 0-shot CoT |
| MATH | 32.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 59.7 | % | 3-shot CoT |
| GPQA | 23.9 | % | 0-shot |
| IFEval | 55.4 | % | prompt_strict |
| ARC | 86.3 | % | challenge |
| MUSR | 50.5 | % | 0-shot |
| WinoGrande | 79.8 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 可靠的通用模型。

## Punti deboli

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Casi d'uso

- 代码生成与调试

## Riferimenti

- [DeepSeek Coder 7B Documentazione](https://api-docs.deepseek.com/)
- Data di rilascio: 2024-01-25
- Fornitore: Deepseek
