---
title: "Capybara 1.5B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Capybara 1.5B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-15
lastmod: 2023-11-15
draft: false
weight: 10
model_id: "capybara-1-5b"
vendor: "other"
version: "capybara-1-5b"
tags: ["open-weights", "self-hostable"]
---

# Capybara 1.5B

## Descripción del modelo

IntrinsicaAI Capybara 1.5B 轻量对话模型, 4K 上下文, 1.5B 参数, 适合边缘设备对话场景。

## Especificaciones principales

| Proveedor | Versión | Fecha de lanzamiento | Ventana de contexto | Modalidades de entrada | Modalidades de salida | Licencia |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | capybara-1-5b | 2023-11-15 | 4K | text | text | Apache 2.0 |

## Rendimiento en benchmarks

| Benchmark | Puntuación | Unidad | Notas |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.7 | % | 5-shot |
| HumanEval | 30.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 28.5 | % | 0-shot CoT |
| MATH | 25.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.3 | % | 3-shot CoT |
| GPQA | 18.1 | % | 0-shot |
| IFEval | 52.4 | % | prompt_strict |
| ARC | 80.1 | % | challenge |
| MUSR | 34.0 | % | 0-shot |
| WinoGrande | 68.9 | % | 0-shot |

## Precios

| Entrada | Salida | Lectura caché | Escritura caché |
|------|--------|-----------|-----------|
| — | — | — | — |

*por millón de tokens*

## Fortalezas

- 可靠的通用模型。

## Debilidades

- MMLU 仅 51.7，知识推理偏弱。
- HumanEval 30.1，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Casos de uso

- 通用对话与问答

## Referencias

- [Capybara 1.5B Documentación](https://huggingface.co/models)
- Fecha de lanzamiento: 2023-11-15
- Proveedor: Other
