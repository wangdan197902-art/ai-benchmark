---
title: "Code Llama 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Code Llama 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-08-24
lastmod: 2023-08-24
draft: false
weight: 10
model_id: "code-llama-7b"
vendor: "meta"
version: "code-llama-7b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Code Llama 7B

## Descripción del modelo

Meta Code Llama 7B 代码专用开源模型, 16K 上下文, 7B 参数, 适合本地代码补全与生成。

## Especificaciones principales

| Proveedor | Versión | Fecha de lanzamiento | Ventana de contexto | Modalidades de entrada | Modalidades de salida | Licencia |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | code-llama-7b | 2023-08-24 | 16K | text | text | Llama 2 Community License |

## Rendimiento en benchmarks

| Benchmark | Puntuación | Unidad | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.5 | % | 5-shot |
| HumanEval | 76.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 52.2 | % | 0-shot CoT |
| MATH | 47.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.9 | % | 3-shot CoT |
| GPQA | 29.5 | % | 0-shot |
| IFEval | 61.2 | % | prompt_strict |
| ARC | 90.1 | % | challenge |
| MUSR | 42.9 | % | 0-shot |
| WinoGrande | 76.3 | % | 0-shot |

## Precios

| Entrada | Salida | Lectura caché | Escritura caché |
|------|--------|-----------|-----------|
| — | — | — | — |

*por millón de tokens*

## Fortalezas

- 可靠的通用模型。

## Debilidades

- MMLU 仅 58.5，知识推理偏弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Casos de uso

- 代码生成与调试

## Referencias

- [Code Llama 7B Documentación](https://llama.meta.com/docs/)
- Fecha de lanzamiento: 2023-08-24
- Proveedor: Meta
