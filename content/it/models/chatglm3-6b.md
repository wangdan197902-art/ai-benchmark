---
title: "ChatGLM3 6B: Complete Benchmark Performance Guide"
description: "In-depth analysis of ChatGLM3 6B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-10-27
lastmod: 2023-10-27
draft: false
weight: 10
model_id: "chatglm3-6b"
vendor: "other"
version: "chatglm3-6b"
tags: ["open-weights", "chinese", "self-hostable", "legacy"]
---

# ChatGLM3 6B

## Panoramica del modello

清华智谱 ChatGLM3 6B 第三代开源模型, 32K 上下文, 6B 参数, 中英双语对话能力突出, 适合本地部署。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | chatglm3-6b | 2023-10-27 | 32K | text | text | GLM-3 License |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.0 | % | 5-shot |
| HumanEval | 51.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 37.9 | % | 0-shot CoT |
| MATH | 31.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 55.7 | % | 3-shot CoT |
| GPQA | 20.1 | % | 0-shot |
| IFEval | 42.5 | % | prompt_strict |
| ARC | 88.9 | % | challenge |
| MUSR | 42.9 | % | 0-shot |
| WinoGrande | 67.7 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 可靠的通用模型。

## Punti deboli

- MMLU 仅 58.0，知识推理偏弱。
- 闭源专有模型，不支持自托管。

## Casi d'uso

- 通用对话与问答

## Riferimenti

- [ChatGLM3 6B Documentazione](https://huggingface.co/models)
- Data di rilascio: 2023-10-27
- Fornitore: Other
