---
title: "Ministral 3B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Ministral 3B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-16
lastmod: 2024-10-16
draft: false
weight: 10
model_id: "ministral-3b"
vendor: "mistral"
version: "ministral-3b"
tags: ["open-weights", "self-hostable", "long-context"]
---

# Ministral 3B

## Descripción del modelo

Mistral Ministral 3B 超轻量边缘模型, 128K 上下文, 3B 参数, 最具性价比的边缘部署模型。

## Especificaciones principales

| Proveedor | Versión | Fecha de lanzamiento | Ventana de contexto | Modalidades de entrada | Modalidades de salida | Licencia |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | ministral-3b | 2024-10-16 | 128K | text | text | Mistral Research License |

## Rendimiento en benchmarks

| Benchmark | Puntuación | Unidad | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 42.4 | % | 5-shot |
| HumanEval | 37.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 32.2 | % | 0-shot CoT |
| MATH | 10.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.1 | % | 3-shot CoT |
| GPQA | 19.0 | % | 0-shot |
| IFEval | 47.8 | % | prompt_strict |
| ARC | 81.5 | % | challenge |
| MUSR | 29.4 | % | 0-shot |
| WinoGrande | 64.8 | % | 0-shot |

## Precios

| Entrada | Salida | Lectura caché | Escritura caché |
|------|--------|-----------|-----------|
| — | — | — | — |

*por millón de tokens*

## Fortalezas

- 上下文窗口 128K，支持长文本。

## Debilidades

- MMLU 仅 42.4，知识推理偏弱。
- HumanEval 37.2，代码能力较弱。
- 闭源专有模型，不支持自托管。

## Casos de uso

- 长文档摘要

## Referencias

- [Ministral 3B Documentación](https://docs.mistral.ai/)
- Fecha de lanzamiento: 2024-10-16
- Proveedor: Mistral
