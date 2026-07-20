---
title: "Yi Large vs Qwen2.5 72B: Benchmark Comparison"
description: "Detailed comparison of Yi Large and Qwen2.5 72B covering benchmarks, pricing, context window, and compliance."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
comparison_id: "yi-large-vs-qwen2-5-72b"
models: ["yi-large", "qwen2-5-72b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "alibaba"]
---

# Yi Large vs Qwen2.5 72B

## Model Overview

Yi Large and Qwen2.5 72B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Key Specifications

| Vendor | Release Date | Context Window | License |
|---------|-------------|----------------|---------|
| Other / Alibaba | 2024-05-13 / 2024-09-19 | 32K / 131K | Proprietary / Qwen License |

## Benchmark Performance

| Benchmark | Yi Large | Qwen2.5 72B | Winner |
|------|------|------|--------|
| ARC | 94.8 | — | A |
| BBH (BIG-Bench Hard) | 77.1 | 82.4 | B |
| GPQA | 35.2 | — | A |
| GSM8K (Grade School Math 8K) | 81.3 | 88.4 | B |
| HumanEval | 72.2 | 86.6 | B |
| IFEval | 73.4 | — | A |
| MATH | 55.9 | 83.1 | B |
| MMLU (Massive Multitask Language Understanding) | 82.8 | 86.1 | B |
| MUSR | 59.4 | — | A |
| WinoGrande | 84.1 | — | A |

## Pricing Comparison

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*per million tokens — A / B*

## Strengths & Weaknesses

### Yi Large

- ✅ MMLU score 82.8, strong knowledge reasoning.
- ⚠️ Proprietary, not self-hostable.

### Qwen2.5 72B

- ✅ MMLU score 86.1, strong knowledge reasoning.
- ✅ HumanEval 86.6, excellent code generation.
- ✅ GSM8K 88.4, robust math reasoning.
- ⚠️ Proprietary, not self-hostable.

## Editor's Take

Yi Large and Qwen2.5 72B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## References

- [Yi Large Documentation](https://huggingface.co/models)
- [Qwen2.5 72B Documentation](https://qwenlm.github.io/)
