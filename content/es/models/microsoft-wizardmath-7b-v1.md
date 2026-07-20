---
title: "Microsoft WizardMath 7B v1: Complete Benchmark Performance Guide"
description: "In-depth analysis of Microsoft WizardMath 7B v1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-08-17
lastmod: 2023-08-17
draft: false
weight: 10
model_id: "microsoft-wizardmath-7b-v1"
vendor: "other"
version: "wizardmath-7b-v1"
tags: ["open-weights", "math", "self-hostable", "legacy"]
---

# Microsoft WizardMath 7B v1

## Descripción del modelo

Microsoft WizardMath 7B v1 数学专用模型, 4K 上下文, 基于 Llama 2 7B, 在 GSM8K 上达到 54.9%。

## Especificaciones principales

| Proveedor | Versión | Fecha de lanzamiento | Ventana de contexto | Modalidades de entrada | Modalidades de salida | Licencia |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardmath-7b-v1 | 2023-08-17 | 4K | text | text | Llama 2 Community License |

## Rendimiento en benchmarks

| Benchmark | Puntuación | Unidad | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.1 | % | 5-shot |
| HumanEval | 61.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.7 | % | 0-shot CoT |
| MATH | 65.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 74.4 | % | 3-shot CoT |
| GPQA | 30.2 | % | 0-shot |
| IFEval | 57.7 | % | prompt_strict |
| ARC | 91.4 | % | challenge |
| MUSR | 53.4 | % | 0-shot |
| WinoGrande | 70.5 | % | 0-shot |

## Precios

| Entrada | Salida | Lectura caché | Escritura caché |
|------|--------|-----------|-----------|
| — | — | — | — |

*por millón de tokens*

## Fortalezas

- 可靠的通用模型。

## Debilidades

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Casos de uso

- 通用对话与问答

## Referencias

- [Microsoft WizardMath 7B v1 Documentación](https://huggingface.co/models)
- Fecha de lanzamiento: 2023-08-17
- Proveedor: Other
