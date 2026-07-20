---
title: "Qwen2.5 72B vs DeepSeek V3: Benchmark Comparison"
description: "Detailed comparison of Qwen2.5 72B and DeepSeek V3 covering benchmarks, pricing, context window, and compliance."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
comparison_id: "qwen2-5-72b-vs-deepseek-v3"
models: ["qwen2-5-72b", "deepseek-v3"]
benchmarks: ["bbh", "gsm8k", "humaneval", "math", "mmlu"]
verdict: "See Editor's Take section."
tags: ["comparison", "alibaba", "deepseek"]
---

# Qwen2.5 72B contra DeepSeek V3

## Descripción del modelo

Qwen2.5 72B and DeepSeek V3 are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Especificaciones clave

| Proveedor | Fecha de lanzamiento | Ventana de contexto | Licencia |
|---------|-------------|----------------|---------|
| Alibaba / Deepseek | 2024-09-19 / 2024-12-26 | 131K / 64K | Qwen License / DeepSeek License |

## Rendimiento en benchmarks

| Benchmark | Qwen2.5 72B | DeepSeek V3 | Ganador |
|------|------|------|--------|
| BBH (BIG-Bench Hard) | 82.4 | 84.9 | B |
| GSM8K (Grade School Math 8K) | 88.4 | 89.3 | B |
| HumanEval | 86.6 | 82.6 | A |
| MATH | 83.1 | 61.6 | A |
| MMLU (Massive Multitask Language Understanding) | 86.1 | 88.5 | B |

## Comparación de precios

| Entrada | Salida | Lectura caché | Escritura caché |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*por millón de tokens — A / B*

## Fortalezas & Debilidades

### Qwen2.5 72B

- ✅ MMLU score 86.1, strong knowledge reasoning.
- ✅ HumanEval 86.6, excellent code generation.
- ✅ GSM8K 88.4, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### DeepSeek V3

- ✅ MMLU score 88.5, strong knowledge reasoning.
- ✅ HumanEval 82.6, excellent code generation.
- ✅ GSM8K 89.3, robust math reasoning.
- ✅ 采用 MoE 混合专家架构。
- ⚠️ 闭源专有模型，不支持自托管。

## Opinión del editor

Qwen2.5 72B and DeepSeek V3 each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Preguntas frecuentes

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referencias

- [Qwen2.5 72B Documentación](https://qwenlm.github.io/)
- [DeepSeek V3 Documentación](https://api-docs.deepseek.com/)
