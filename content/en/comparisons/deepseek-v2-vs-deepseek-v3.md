---
title: "DeepSeek V2 vs DeepSeek V3: Benchmark Comparison"
description: "Detailed comparison of DeepSeek V2 and DeepSeek V3 covering benchmarks, pricing, context window, and compliance."
date: 2024-05-07
lastmod: 2024-05-07
draft: false
weight: 10
comparison_id: "deepseek-v2-vs-deepseek-v3"
models: ["deepseek-v2", "deepseek-v3"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "deepseek", "deepseek"]
---

# DeepSeek V2 vs DeepSeek V3

## Model Overview

DeepSeek V2 and DeepSeek V3 are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Key Specifications

| Vendor | Release Date | Context Window | License |
|---------|-------------|----------------|---------|
| Deepseek / Deepseek | 2024-05-07 / 2024-12-26 | 32K / 64K | DeepSeek License / DeepSeek License |

## Benchmark Performance

| Benchmark | DeepSeek V2 | DeepSeek V3 | Winner |
|------|------|------|--------|
| ARC | 92.1 | — | A |
| BBH (BIG-Bench Hard) | 70.5 | 84.9 | B |
| GPQA | 31.5 | — | A |
| GSM8K (Grade School Math 8K) | 78.8 | 89.3 | B |
| HumanEval | 75.7 | 82.6 | B |
| IFEval | 78.6 | — | A |
| MATH | 35.2 | 61.6 | B |
| MMLU (Massive Multitask Language Understanding) | 78.2 | 88.5 | B |
| MUSR | 53.4 | — | A |
| WinoGrande | 84.7 | — | A |

## Pricing Comparison

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*per million tokens — A / B*

## Strengths & Weaknesses

### DeepSeek V2

- ✅ Mixture-of-Experts architecture.
- ⚠️ Proprietary, not self-hostable.

### DeepSeek V3

- ✅ MMLU score 88.5, strong knowledge reasoning.
- ✅ HumanEval 82.6, excellent code generation.
- ✅ GSM8K 89.3, robust math reasoning.
- ✅ Mixture-of-Experts architecture.
- ⚠️ Proprietary, not self-hostable.

## Editor's Take

DeepSeek V2 and DeepSeek V3 each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## References

- [DeepSeek V2 Documentation](https://api-docs.deepseek.com/)
- [DeepSeek V3 Documentation](https://api-docs.deepseek.com/)
