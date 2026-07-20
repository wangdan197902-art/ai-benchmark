---
title: "Mistral Large 2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Large 2 across MMLU, HumanEval, GSM8K, MATH, and BBH benchmarks with pricing and EU residency considerations."
date: 2024-07-24
lastmod: 2024-08-15
draft: false
weight: 80
model_id: "mistral-large-2"
vendor: "mistral"
version: "large-2"
tags: ["flagship", "coding", "eu-residency"]
---

# Mistral Large 2

## Model Overview

Mistral Large 2 is Mistral AI's flagship model, released on July 24, 2024. With 123B parameters and a 128K context window, it is designed to compete with GPT-4o and Claude 3.5 Sonnet on coding, mathematics, and multilingual reasoning. Mistral Large 2 is particularly notable for its European sovereignty story: it is developed by a Paris-headquartered company, supports EU data residency, and is compliant with GDPR and ISO 27001 — making it a preferred choice for European enterprises and public sector organizations with strict data sovereignty requirements. The model supports dozens of languages natively and achieves a 92.0 pass@1 on HumanEval, placing it among the top coding models. Mistral Large 2 is available via the Mistral API, La Plateforme, Azure AI, and Google Cloud Vertex AI.

## Key Specifications

| Attribute | Value |
|-----------|-------|
| Vendor | Mistral AI |
| Version | large-2 |
| Release Date | 2024-07-24 |
| Context Window | 128,000 tokens |
| Input Modalities | text |
| Output Modalities | text |
| License | Mistral Research License |
| Documentation | https://docs.mistral.ai/ |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|-----------|-------|------|-------|
| MMLU | 84.0 | % | 5-shot |
| HumanEval | 92.0 | pass@1 | — |
| GSM8K | 93.0 | % | 0-shot CoT |
| MATH | 71.0 | % | 0-shot CoT |
| BBH | 81.0 | % | 3-shot CoT |

## Pricing

| Tier | Price (per 1M tokens) |
|------|------------------------|
| Input | $2.00 |
| Output | $6.00 |
| Cache Read | $0.00 |
| Cache Write | $0.00 |

Pricing source: https://mistral.ai/technology/ (as of 2024-08-01).

## Strengths

- Top-tier coding performance (HumanEval 92.0), matching Claude 3.5 Sonnet.
- EU data residency with GDPR and ISO 27001 compliance.
- Strong multilingual coverage across European languages.
- Competitive pricing — 20% cheaper than GPT-4o on input tokens.

## Weaknesses

- Text-only model; no native multimodal support.
- Mistral Research License restricts commercial use for non-Mistral customers.
- MMLU score (84.0) trails leading flagships like GPT-4o (88.7).

## Use Cases

- European enterprise deployments requiring GDPR-compliant data residency.
- Code generation and refactoring workflows.
- Multilingual customer service across EU markets.
- Public sector and regulated industries needing ISO 27001 certification.

## References

- [Mistral Large 2 Announcement](https://mistral.ai/news/mistral-large-2407/)
- [Mistral AI Documentation](https://docs.mistral.ai/)
- [Mistral Technology Page](https://mistral.ai/technology/)
