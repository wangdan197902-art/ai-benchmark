---
title: "Claude 3.5 Sonnet vs Qwen2.5 72B: Benchmark Comparison"
description: "Detailed comparison of Claude 3.5 Sonnet and Qwen2.5 72B covering benchmarks, pricing, context window, and compliance."
date: 2024-06-20
lastmod: 2024-06-20
draft: false
weight: 10
comparison_id: "claude-3-5-sonnet-vs-qwen2-5-72b"
models: ["claude-3-5-sonnet", "qwen2-5-72b"]
benchmarks: ["bbh", "gsm8k", "humaneval", "math", "mmlu"]
verdict: "See Editor's Take section."
tags: ["comparison", "anthropic", "alibaba"]
---

# Claude 3.5 Sonnet contra Qwen2.5 72B

## Descripción del modelo

Claude 3.5 Sonnet and Qwen2.5 72B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Especificaciones clave

| Proveedor | Fecha de lanzamiento | Ventana de contexto | Licencia |
|---------|-------------|----------------|---------|
| Anthropic / Alibaba | 2024-06-20 / 2024-09-19 | 200K / 131K | Proprietary / Qwen License |

## Rendimiento en benchmarks

| Benchmark | Claude 3.5 Sonnet | Qwen2.5 72B | Ganador |
|------|------|------|--------|
| BBH (BIG-Bench Hard) | 84.5 | 82.4 | A |
| GSM8K (Grade School Math 8K) | 96.4 | 88.4 | A |
| HumanEval | 92.0 | 86.6 | A |
| MATH | 71.1 | 83.1 | B |
| MMLU (Massive Multitask Language Understanding) | 88.7 | 86.1 | A |

## Comparación de precios

| Entrada | Salida | Lectura caché | Escritura caché |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*por millón de tokens — A / B*

## Fortalezas & Debilidades

### Claude 3.5 Sonnet

- ✅ MMLU score 88.7, strong knowledge reasoning.
- ✅ HumanEval 92.0, excellent code generation.
- ✅ GSM8K 96.4, robust math reasoning.
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

### Qwen2.5 72B

- ✅ MMLU score 86.1, strong knowledge reasoning.
- ✅ HumanEval 86.6, excellent code generation.
- ✅ GSM8K 88.4, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## Opinión del editor

Claude 3.5 Sonnet and Qwen2.5 72B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Preguntas frecuentes

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referencias

- [Claude 3.5 Sonnet Documentación](https://docs.anthropic.com/claude/docs)
- [Qwen2.5 72B Documentación](https://qwenlm.github.io/)
