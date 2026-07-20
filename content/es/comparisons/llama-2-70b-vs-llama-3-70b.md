---
title: "Llama 2 70B vs Llama 3 70B: Benchmark Comparison"
description: "Detailed comparison of Llama 2 70B and Llama 3 70B covering benchmarks, pricing, context window, and compliance."
date: 2023-07-18
lastmod: 2023-07-18
draft: false
weight: 10
comparison_id: "llama-2-70b-vs-llama-3-70b"
models: ["llama-2-70b", "llama-3-70b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "meta", "meta"]
---

# Llama 2 70B contra Llama 3 70B

## Descripción del modelo

Llama 2 70B and Llama 3 70B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Especificaciones clave

| Proveedor | Fecha de lanzamiento | Ventana de contexto | Licencia |
|---------|-------------|----------------|---------|
| Meta / Meta | 2023-07-18 / 2024-04-18 | 4K / 8K | Llama 2 Community License / Llama 3 Community License |

## Rendimiento en benchmarks

| Benchmark | Llama 2 70B | Llama 3 70B | Ganador |
|------|------|------|--------|
| ARC | 80.3 | 93.4 | B |
| BBH (BIG-Bench Hard) | 62.5 | 77.6 | B |
| GPQA | 27.2 | 38.2 | B |
| GSM8K (Grade School Math 8K) | 51.8 | 76.2 | B |
| HumanEval | 50.6 | 73.0 | B |
| IFEval | 57.1 | 72.2 | B |
| MATH | 22.4 | 50.1 | B |
| MMLU (Massive Multitask Language Understanding) | 53.0 | 79.5 | B |
| MUSR | 36.1 | 51.2 | B |
| WinoGrande | 73.4 | 79.2 | B |

## Comparación de precios

| Entrada | Salida | Lectura caché | Escritura caché |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*por millón de tokens — A / B*

## Fortalezas & Debilidades

### Llama 2 70B

- ✅ 可靠的通用模型。
- ⚠️ MMLU 仅 53.0，知识推理偏弱。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 4K 偏小。

### Llama 3 70B

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 8K 偏小。

## Opinión del editor

Llama 2 70B and Llama 3 70B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Preguntas frecuentes

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referencias

- [Llama 2 70B Documentación](https://llama.meta.com/docs/)
- [Llama 3 70B Documentación](https://llama.meta.com/docs/)
