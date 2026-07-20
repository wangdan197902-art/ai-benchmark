---
title: "Jamba 1.5 Mini: Complete Benchmark Performance Guide"
description: "In-depth analysis of Jamba 1.5 Mini performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-07
lastmod: 2024-08-07
draft: false
weight: 10
model_id: "jamba-1-5-mini"
vendor: "other"
version: "jamba-1-5-mini"
tags: ["open-weights", "moe", "long-context"]
---

# Jamba 1.5 Mini

## Descripción del modelo

AI21 Labs Jamba 1.5 Mini 混合模型, 256K 上下文, 总参 52B/活跃 12B, 经济型长上下文模型。

## Especificaciones principales

| Proveedor | Versión | Fecha de lanzamiento | Ventana de contexto | Modalidades de entrada | Modalidades de salida | Licencia |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | jamba-1-5-mini | 2024-08-07 | 256K | text | text | Jamba Open Model License |

## Rendimiento en benchmarks

| Benchmark | Puntuación | Unidad | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.9 | % | 5-shot |
| HumanEval | 67.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.7 | % | 0-shot CoT |
| MATH | 42.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.6 | % | 3-shot CoT |
| GPQA | 34.2 | % | 0-shot |
| IFEval | 71.9 | % | prompt_strict |
| ARC | 91.8 | % | challenge |
| MUSR | 48.1 | % | 0-shot |
| WinoGrande | 81.0 | % | 0-shot |

## Precios

| Entrada | Salida | Lectura caché | Escritura caché |
|------|--------|-----------|-----------|
| — | — | — | — |

*por millón de tokens*

## Fortalezas

- 上下文窗口 256K，支持长文本。
- 采用 MoE 混合专家架构。

## Debilidades

- 闭源专有模型，不支持自托管。

## Casos de uso

- 长文档摘要

## Referencias

- [Jamba 1.5 Mini Documentación](https://huggingface.co/models)
- Fecha de lanzamiento: 2024-08-07
- Proveedor: Other
