---
title: "Jamba 1.5 Large vs Mistral Large 2: Benchmark Comparison"
description: "Detailed comparison of Jamba 1.5 Large and Mistral Large 2 covering benchmarks, pricing, context window, and compliance."
date: 2024-08-07
lastmod: 2024-08-07
draft: false
weight: 10
comparison_id: "jamba-1-5-large-vs-mistral-large-2"
models: ["jamba-1-5-large", "mistral-large-2"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "mistral"]
---

# Jamba 1.5 Large contra Mistral Large 2

## Descripción del modelo

Jamba 1.5 Large and Mistral Large 2 are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Especificaciones clave

| Proveedor | Fecha de lanzamiento | Ventana de contexto | Licencia |
|---------|-------------|----------------|---------|
| Other / Mistral | 2024-08-07 / 2024-07-24 | 256K / 128K | Jamba Open Model License / Mistral Research License |

## Rendimiento en benchmarks

| Benchmark | Jamba 1.5 Large | Mistral Large 2 | Ganador |
|------|------|------|--------|
| ARC | 93.8 | — | A |
| BBH (BIG-Bench Hard) | 82.8 | 81.0 | A |
| GPQA | 50.8 | — | A |
| GSM8K (Grade School Math 8K) | 83.5 | 93.0 | B |
| HumanEval | 73.7 | 92.0 | B |
| IFEval | 70.8 | — | A |
| MATH | 60.0 | 71.0 | B |
| MMLU (Massive Multitask Language Understanding) | 84.3 | 84.0 | Tie |
| MUSR | 51.1 | — | A |
| WinoGrande | 84.3 | — | A |

## Comparación de precios

| Entrada | Salida | Lectura caché | Escritura caché |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*por millón de tokens — A / B*

## Fortalezas & Debilidades

### Jamba 1.5 Large

- ✅ MMLU score 84.3, strong knowledge reasoning.
- ✅ 上下文窗口 256K，支持长文本。
- ✅ 采用 MoE 混合专家架构。
- ⚠️ 闭源专有模型，不支持自托管。

### Mistral Large 2

- ✅ MMLU score 84.0, strong knowledge reasoning.
- ✅ HumanEval 92.0, excellent code generation.
- ✅ GSM8K 93.0, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## Opinión del editor

Jamba 1.5 Large and Mistral Large 2 each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Preguntas frecuentes

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referencias

- [Jamba 1.5 Large Documentación](https://huggingface.co/models)
- [Mistral Large 2 Documentación](https://docs.mistral.ai/)
