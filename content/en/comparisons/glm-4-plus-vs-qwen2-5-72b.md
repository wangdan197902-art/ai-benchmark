---
title: "GLM-4 Plus vs Qwen2.5 72B: Benchmark Comparison"
description: "Detailed comparison of GLM-4 Plus and Qwen2.5 72B covering benchmarks, pricing, context window, and compliance."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
comparison_id: "glm-4-plus-vs-qwen2-5-72b"
models: ["glm-4-plus", "qwen2-5-72b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "alibaba"]
---

# GLM-4 Plus vs Qwen2.5 72B

## Model Overview

GLM-4 Plus and Qwen2.5 72B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Key Specifications

| Vendor | Release Date | Context Window | License |
|---------|-------------|----------------|---------|
| Other / Alibaba | 2024-08-12 / 2024-09-19 | 131K / 131K | Proprietary / Qwen License |

## Benchmark Performance

| Benchmark | GLM-4 Plus | Qwen2.5 72B | Winner |
|------|------|------|--------|
| ARC | 94.5 | — | A |
| BBH (BIG-Bench Hard) | 83.6 | 82.4 | A |
| GPQA | 35.4 | — | A |
| GSM8K (Grade School Math 8K) | 81.8 | 88.4 | B |
| HumanEval | 72.7 | 86.6 | B |
| IFEval | 79.2 | — | A |
| MATH | 53.3 | 83.1 | B |
| MMLU (Massive Multitask Language Understanding) | 84.3 | 86.1 | B |
| MUSR | 51.3 | — | A |
| WinoGrande | 85.8 | — | A |

## Pricing Comparison

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*per million tokens — A / B*

## Strengths & Weaknesses

### GLM-4 Plus

- ✅ MMLU score 84.3, strong knowledge reasoning.
- ✅ Input Modalities: text, image, audio.
- ⚠️ Proprietary, not self-hostable.

### Qwen2.5 72B

- ✅ MMLU score 86.1, strong knowledge reasoning.
- ✅ HumanEval 86.6, excellent code generation.
- ✅ GSM8K 88.4, robust math reasoning.
- ⚠️ Proprietary, not self-hostable.

## Editor's Take

GLM-4 Plus and Qwen2.5 72B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## References

- [GLM-4 Plus Documentation](https://huggingface.co/models)
- [Qwen2.5 72B Documentation](https://qwenlm.github.io/)
