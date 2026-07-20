---
title: "Gemini 1.5 Flash 002: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.5 Flash 002 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-24
lastmod: 2024-09-24
draft: false
weight: 10
model_id: "gemini-1-5-flash-002"
vendor: "google"
version: "1.5-flash-002"
tags: ["multimodal", "realtime", "long-context"]
---

# Gemini 1.5 Flash 002

## Descripción del modelo

Google Gemini 1.5 Flash 002 生产版本, 1M 上下文, 改进质量与稳定性。

## Especificaciones principales

| Proveedor | Versión | Fecha de lanzamiento | Ventana de contexto | Modalidades de entrada | Modalidades de salida | Licencia |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.5-flash-002 | 2024-09-24 | 1000K | text, image, audio, video | text | Proprietary |

## Rendimiento en benchmarks

| Benchmark | Puntuación | Unidad | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.1 | % | 5-shot |
| HumanEval | 66.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.8 | % | 0-shot CoT |
| MATH | 40.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.8 | % | 3-shot CoT |
| GPQA | 32.0 | % | 0-shot |
| IFEval | 77.2 | % | prompt_strict |
| ARC | 91.8 | % | challenge |
| MUSR | 59.8 | % | 0-shot |
| WinoGrande | 81.9 | % | 0-shot |

## Precios

| Entrada | Salida | Lectura caché | Escritura caché |
|------|--------|-----------|-----------|
| — | — | — | — |

*por millón de tokens*

## Fortalezas

- MMLU score 81.1, strong knowledge reasoning.
- 支持文本、图像、音频多模态输入。
- 上下文窗口 1000K，支持长文本。

## Debilidades

- 闭源专有模型，不支持自托管。

## Casos de uso

- 长文档摘要
- 视觉与图像理解

## Referencias

- [Gemini 1.5 Flash 002 Documentación](https://ai.google.dev/gemini-api/docs)
- Fecha de lanzamiento: 2024-09-24
- Proveedor: Google
