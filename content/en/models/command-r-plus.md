---
title: "Command R+: Complete Benchmark Performance Guide"
description: "In-depth analysis of Cohere Command R+ across MMLU, HumanEval, GSM8K, MATH, and BBH benchmarks with pricing and enterprise RAG considerations."
date: 2024-04-04
lastmod: 2024-08-15
draft: false
weight: 90
model_id: "command-r-plus"
vendor: "cohere"
version: "r-plus"
tags: ["rag", "enterprise", "tool-use"]
---

# Command R+

## Model Overview

Command R+ is Cohere's enterprise-focused flagship, released on April 4, 2024. With 104B parameters and a 128K context window, the model is specifically optimized for retrieval-augmented generation (RAG), tool use, and structured output — workflows that dominate enterprise production deployments. Cohere positions Command R+ as the model of choice for organizations building production-grade RAG pipelines, citing its industry-leading citation quality and groundedness. The model ships with native support for tool calling, JSON-mode output, and multi-step reasoning over retrieved documents. Cohere also emphasizes data privacy: customer prompts are never used for training, and the model is available on AWS, Azure, Google Cloud, and Oracle Cloud with SOC2, GDPR, and ISO 27001 compliance certifications. Command R+ is licensed under CC-BY-NC-4.0 for non-commercial research use, with commercial use available via the Cohere API.

## Key Specifications

| Attribute | Value |
|-----------|-------|
| Vendor | Cohere |
| Version | r-plus |
| Release Date | 2024-04-04 |
| Context Window | 128,000 tokens |
| Input Modalities | text |
| Output Modalities | text |
| License | CC-BY-NC-4.0 (research); commercial via Cohere API |
| Documentation | https://docs.cohere.com/docs/command-r-plus |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|-----------|-------|------|-------|
| MMLU | 75.0 | % | 5-shot |
| HumanEval | 70.7 | pass@1 | — |
| GSM8K | 68.4 | % | 0-shot CoT |
| MATH | 35.6 | % | 0-shot CoT |
| BBH | 66.1 | % | 3-shot CoT |

## Pricing

| Tier | Price (per 1M tokens) |
|------|------------------------|
| Input | $2.50 |
| Output | $10.00 |
| Cache Read | $0.00 |
| Cache Write | $0.00 |

Pricing source: https://cohere.com/pricing (as of 2024-08-01).

## Strengths

- Industry-leading RAG performance with strong citation and groundedness.
- Native tool calling and structured output for agentic workflows.
- Enterprise-grade compliance: SOC2, GDPR, ISO 27001, with no-training privacy guarantee.
- Available across all major cloud providers.

## Weaknesses

- General reasoning benchmarks (MMLU 75.0) trail leading flagships significantly.
- Non-commercial CC-BY-NC-4.0 license prevents self-hosting for production use.
- Pricing matches GPT-4o despite lower raw benchmark performance.

## Use Cases

- Production RAG pipelines for legal, financial, and healthcare knowledge bases.
- Customer support automation with grounded citations.
- Enterprise agentic workflows involving tool calls and structured outputs.
- Multilingual enterprise search with strict data residency requirements.

## References

- [Command R+ Announcement — Cohere](https://txt.cohere.com/command-r-plus-microsoft-azure)
- [Cohere Pricing](https://cohere.com/pricing)
- [Command R+ Documentation](https://docs.cohere.com/docs/command-r-plus)
