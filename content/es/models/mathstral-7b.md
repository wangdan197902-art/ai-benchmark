---
title: "Mathstral 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mathstral 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-16
lastmod: 2024-07-16
draft: false
weight: 10
model_id: "mathstral-7b"
vendor: "mistral"
version: "mathstral-7b"
tags: ["math", "open-weights", "self-hostable"]
---

# Mathstral 7B

## Descripción del modelo

Mistral Mathstral 7B 数学专用模型, 32K 上下文, 基于 Mistral 7B 微调, 在 MATH 基准上达到 56.6%。

## Especificaciones principales

| Proveedor | Versión | Fecha de lanzamiento | Ventana de contexto | Modalidades de entrada | Modalidades de salida | Licencia |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | mathstral-7b | 2024-07-16 | 32K | text | text | Apache 2.0 |

## Rendimiento en benchmarks

| Benchmark | Puntuación | Unidad | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.1 | % | 5-shot |
| HumanEval | 49.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 72.4 | % | 0-shot CoT |
| MATH | 61.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 69.8 | % | 3-shot CoT |
| GPQA | 37.5 | % | 0-shot |
| IFEval | 63.6 | % | prompt_strict |
| ARC | 91.5 | % | challenge |
| MUSR | 42.3 | % | 0-shot |
| WinoGrande | 71.0 | % | 0-shot |

## Precios

| Entrada | Salida | Lectura caché | Escritura caché |
|------|--------|-----------|-----------|
| — | — | — | — |

*por millón de tokens*

## Fortalezas

- 可靠的通用模型。

## Debilidades

- HumanEval 49.9，代码能力较弱。
- 闭源专有模型，不支持自托管。

## Casos de uso

- 通用对话与问答

## Referencias

- [Mathstral 7B Documentación](https://docs.mistral.ai/)
- Fecha de lanzamiento: 2024-07-16
- Proveedor: Mistral
