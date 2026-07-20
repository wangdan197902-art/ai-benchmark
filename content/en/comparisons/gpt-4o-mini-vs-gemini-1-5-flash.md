---
title: "GPT-4o mini vs Gemini 1.5 Flash: Benchmark Comparison"
description: "Detailed comparison of GPT-4o mini and Gemini 1.5 Flash covering benchmarks, pricing, context window, and compliance."
date: 2024-07-18
lastmod: 2024-07-18
draft: false
weight: 10
comparison_id: "gpt-4o-mini-vs-gemini-1-5-flash"
models: ["gpt-4o-mini", "gemini-1-5-flash"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "google"]
---

# GPT-4o mini vs Gemini 1.5 Flash

## Model Overview

GPT-4o mini and Gemini 1.5 Flash are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Key Specifications

| Vendor | Release Date | Context Window | License |
|---------|-------------|----------------|---------|
| Openai / Google | 2024-07-18 / 2024-05-14 | 128K / 1000K | Proprietary / Proprietary |

## Benchmark Performance

| Benchmark | GPT-4o mini | Gemini 1.5 Flash | Winner |
|------|------|------|--------|
| ARC | 93.9 | 93.4 | A |
| BBH (BIG-Bench Hard) | 70.3 | 71.7 | B |
| GPQA | 42.6 | 38.5 | A |
| GSM8K (Grade School Math 8K) | 75.1 | 75.2 | Tie |
| HumanEval | 78.0 | 67.5 | A |
| IFEval | 67.9 | 68.0 | Tie |
| MATH | 51.8 | 53.2 | B |
| MMLU (Massive Multitask Language Understanding) | 79.7 | 76.0 | A |
| MUSR | 53.1 | 46.1 | A |
| WinoGrande | 79.6 | 78.9 | A |

## Pricing Comparison

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*per million tokens — A / B*

## Strengths & Weaknesses

### GPT-4o mini

- ✅ Input Modalities: text, image, audio.
- ⚠️ Proprietary, not self-hostable.

### Gemini 1.5 Flash

- ✅ Input Modalities: text, image, audio.
- ✅ Context window 1000K.
- ⚠️ Proprietary, not self-hostable.

## Editor's Take

GPT-4o mini and Gemini 1.5 Flash each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## References

- [GPT-4o mini Documentation](https://platform.openai.com/docs/models)
- [Gemini 1.5 Flash Documentation](https://ai.google.dev/gemini-api/docs)
