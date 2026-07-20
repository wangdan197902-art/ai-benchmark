---
title: "Command Nightly: Complete Benchmark Performance Guide"
description: "In-depth analysis of Command Nightly performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-01
lastmod: 2024-01-01
draft: false
weight: 10
model_id: "command-nightly"
vendor: "cohere"
version: "nightly"
tags: ["rag", "enterprise"]
---

# Command Nightly

## Descripción del modelo

Cohere Command Nightly 实验版模型, 128K 上下文, 最新功能预览, 适合测试新特性。

## Especificaciones principales

| Proveedor | Versión | Fecha de lanzamiento | Ventana de contexto | Modalidades de entrada | Modalidades de salida | Licencia |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | nightly | 2024-01-01 | 128K | text | text | CC-BY-NC-4.0 |

## Rendimiento en benchmarks

| Benchmark | Puntuación | Unidad | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 85.2 | % | 5-shot |
| HumanEval | 74.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 87.2 | % | 0-shot CoT |
| MATH | 49.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.7 | % | 3-shot CoT |
| GPQA | 45.5 | % | 0-shot |
| IFEval | 80.8 | % | prompt_strict |
| ARC | 95.9 | % | challenge |
| MUSR | 57.5 | % | 0-shot |
| WinoGrande | 80.8 | % | 0-shot |

## Precios

| Entrada | Salida | Lectura caché | Escritura caché |
|------|--------|-----------|-----------|
| — | — | — | — |

*por millón de tokens*

## Fortalezas

- MMLU score 85.2, strong knowledge reasoning.
- GSM8K 87.2, robust math reasoning.
- 企业级合规认证。

## Debilidades

- 闭源专有模型，不支持自托管。

## Casos de uso

- 代码生成与调试
- 企业客户支持

## Referencias

- [Command Nightly Documentación](https://docs.cohere.com/docs)
- Fecha de lanzamiento: 2024-01-01
- Proveedor: Cohere
