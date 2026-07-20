---
title: "Yi Large Turbo: Complete Benchmark Performance Guide"
description: "In-depth analysis of Yi Large Turbo performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-24
lastmod: 2024-07-24
draft: false
weight: 10
model_id: "yi-large-turbo"
vendor: "other"
version: "yi-large-turbo"
tags: ["flagship", "chinese", "realtime"]
---

# Yi Large Turbo

## Descripción del modelo

01.AI Yi Large Turbo 经济型旗舰, 16K 上下文, 速度快成本低, 性能接近 Yi Large。

## Especificaciones principales

| Proveedor | Versión | Fecha de lanzamiento | Ventana de contexto | Modalidades de entrada | Modalidades de salida | Licencia |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | yi-large-turbo | 2024-07-24 | 16K | text | text | Proprietary |

## Rendimiento en benchmarks

| Benchmark | Puntuación | Unidad | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.4 | % | 5-shot |
| HumanEval | 72.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 81.0 | % | 0-shot CoT |
| MATH | 42.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.4 | % | 3-shot CoT |
| GPQA | 38.2 | % | 0-shot |
| IFEval | 70.7 | % | prompt_strict |
| ARC | 95.6 | % | challenge |
| MUSR | 63.7 | % | 0-shot |
| WinoGrande | 82.3 | % | 0-shot |

## Precios

| Entrada | Salida | Lectura caché | Escritura caché |
|------|--------|-----------|-----------|
| — | — | — | — |

*por millón de tokens*

## Fortalezas

- MMLU score 84.4, strong knowledge reasoning.

## Debilidades

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Casos de uso

- 代码生成与调试
- Agent 工作流与工具调用

## Referencias

- [Yi Large Turbo Documentación](https://huggingface.co/models)
- Fecha de lanzamiento: 2024-07-24
- Proveedor: Other
