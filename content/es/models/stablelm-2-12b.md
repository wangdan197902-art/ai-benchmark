---
title: "StableLM 2 12B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StableLM 2 12B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-19
lastmod: 2024-01-19
draft: false
weight: 10
model_id: "stablelm-2-12b"
vendor: "other"
version: "stablelm-2-12b"
tags: ["open-weights", "self-hostable"]
---

# StableLM 2 12B

## Descripción del modelo

Stability AI StableLM 2 12B 模型, 4K 上下文, 多语言训练, 支持 7 种语言, 性能接近 Llama 2 13B。

## Especificaciones principales

| Proveedor | Versión | Fecha de lanzamiento | Ventana de contexto | Modalidades de entrada | Modalidades de salida | Licencia |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | stablelm-2-12b | 2024-01-19 | 4K | text | text | Stability AI Community License |

## Rendimiento en benchmarks

| Benchmark | Puntuación | Unidad | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.7 | % | 5-shot |
| HumanEval | 76.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.1 | % | 0-shot CoT |
| MATH | 37.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.6 | % | 3-shot CoT |
| GPQA | 44.0 | % | 0-shot |
| IFEval | 80.0 | % | prompt_strict |
| ARC | 94.9 | % | challenge |
| MUSR | 58.1 | % | 0-shot |
| WinoGrande | 84.1 | % | 0-shot |

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

- 代码生成与调试

## Referencias

- [StableLM 2 12B Documentación](https://huggingface.co/models)
- Fecha de lanzamiento: 2024-01-19
- Proveedor: Other
