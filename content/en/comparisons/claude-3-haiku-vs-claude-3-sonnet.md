---
title: "Claude 3 Haiku vs Claude 3 Sonnet: Benchmark Comparison"
description: "Detailed comparison of Claude 3 Haiku and Claude 3 Sonnet covering benchmarks, pricing, context window, and compliance."
date: 2024-03-07
lastmod: 2024-03-07
draft: false
weight: 10
comparison_id: "claude-3-haiku-vs-claude-3-sonnet"
models: ["claude-3-haiku", "claude-3-sonnet"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "anthropic", "anthropic"]
---

# Claude 3 Haiku vs Claude 3 Sonnet

## Model Overview

Claude 3 Haiku and Claude 3 Sonnet are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Key Specifications

| Vendor | Release Date | Context Window | License |
|---------|-------------|----------------|---------|
| Anthropic / Anthropic | 2024-03-07 / 2024-03-04 | 200K / 200K | Proprietary / Proprietary |

## Benchmark Performance

| Benchmark | Claude 3 Haiku | Claude 3 Sonnet | Winner |
|------|------|------|--------|
| ARC | 94.3 | 94.8 | B |
| BBH (BIG-Bench Hard) | 75.7 | 76.1 | Tie |
| GPQA | 44.4 | 35.9 | A |
| GSM8K (Grade School Math 8K) | 82.2 | 84.0 | B |
| HumanEval | 69.4 | 74.5 | B |
| IFEval | 70.8 | 74.3 | B |
| MATH | 52.2 | 42.4 | A |
| MMLU (Massive Multitask Language Understanding) | 77.9 | 81.5 | B |
| MUSR | 58.1 | 64.1 | B |
| WinoGrande | 84.8 | 83.8 | A |

## Pricing Comparison

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*per million tokens — A / B*

## Strengths & Weaknesses

### Claude 3 Haiku

- ✅ Reliable general-purpose model.
- ⚠️ Proprietary, not self-hostable.

### Claude 3 Sonnet

- ✅ MMLU score 81.5, strong knowledge reasoning.
- ✅ Input Modalities: text, image, audio.
- ✅ Context window 200K.
- ⚠️ Proprietary, not self-hostable.

## Editor's Take

Claude 3 Haiku and Claude 3 Sonnet each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## References

- [Claude 3 Haiku Documentation](https://docs.anthropic.com/claude/docs)
- [Claude 3 Sonnet Documentation](https://docs.anthropic.com/claude/docs)
