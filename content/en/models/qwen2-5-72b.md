---
title: "Qwen2.5 72B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Alibaba's Qwen2.5 72B across MMLU, HumanEval, GSM8K, MATH, and BBH benchmarks with pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 60
model_id: "qwen2-5-72b"
vendor: "alibaba"
version: "2.5-72b"
tags: ["open-weights", "chinese", "coding"]
---

# Qwen2.5 72B

## Model Overview

Qwen2.5 72B is Alibaba's flagship open-weights model, released on September 19, 2024 as part of the Qwen2.5 series. The model delivers leading Chinese-language understanding, strong multilingual coverage across 29+ languages, and a 131K context window. On academic benchmarks, Qwen2.5 72B matches or exceeds Llama 3.1 70B on MMLU (86.1) and significantly outperforms it on math (83.1 vs 71.8) and coding (86.6 HumanEval pass@1). Released under the Qwen License — which permits commercial use with minimal restrictions — Qwen2.5 72B has become a top choice for Chinese-market deployments, bilingual RAG systems, and code-generation pipelines where Chinese context matters. The model ships with native support for structured output, tool calling, and long-document summarization.

## Key Specifications

| Attribute | Value |
|-----------|-------|
| Vendor | Alibaba |
| Version | 2.5-72b |
| Release Date | 2024-09-19 |
| Context Window | 131,072 tokens |
| Input Modalities | text |
| Output Modalities | text |
| License | Qwen License |
| Documentation | https://qwenlm.github.io/ |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|-----------|-------|------|-------|
| MMLU | 86.1 | % | 5-shot |
| HumanEval | 86.6 | pass@1 | — |
| GSM8K | 88.4 | % | 0-shot CoT |
| MATH | 83.1 | % | 0-shot CoT |
| BBH | 82.4 | % | 3-shot CoT |

## Pricing

| Tier | Price (per 1M tokens) |
|------|------------------------|
| Input (Alibaba Cloud) | $0.50 |
| Output (Alibaba Cloud) | $0.80 |
| Cache Read | $0.00 |
| Cache Write | $0.00 |

Pricing source: https://help.aliyun.com/zh/model-studio/getting-started/models (as of 2024-09-19). Open-weights license also allows self-hosting.

## Strengths

- Best-in-class Chinese language understanding among open-weights models.
- Strong coding and math performance, surpassing Llama 3.1 70B on multiple benchmarks.
- 131K context window handles long Chinese documents and codebases.
- Competitive API pricing at $0.50/$0.80 per million tokens.

## Weaknesses

- Qwen License has minor commercial restrictions vs Apache 2.0.
- Vendor ecosystem is China-centric; community tooling outside Alibaba Cloud is less mature.
- No native multimodal support in the 72B text variant (Qwen2.5-VL is a separate model).

## Use Cases

- Chinese-market customer service and content generation.
- Bilingual RAG systems requiring balanced EN/ZH retrieval.
- Code generation pipelines targeting Chinese developer audiences.
- Academic research needing strong math and reasoning at lower cost.

## References

- [Qwen2.5 Blog Post](https://qwenlm.github.io/blog/qwen2.5/)
- [Alibaba Model Studio](https://help.aliyun.com/zh/model-studio/getting-started/models)
- [Qwen Documentation](https://qwenlm.github.io/)
