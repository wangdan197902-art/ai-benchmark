---
title: "Gemini 1.5 Pro: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.5 Pro's performance across MMLU, HumanEval, GSM8K, MATH, and BBH benchmarks with pricing and use cases."
date: 2024-02-15
lastmod: 2024-08-15
draft: false
weight: 30
model_id: "gemini-1-5-pro"
vendor: "google"
version: "1.5-pro"
tags: ["flagship", "multimodal", "long-context"]
---

# Gemini 1.5 Pro

## Model Overview

Gemini 1.5 Pro is Google DeepMind's flagship multimodal model, released on February 15, 2024. Its standout feature is the industry-leading 2 million token context window, enabling whole-codebase reasoning, multi-hour video understanding, and million-word document analysis in a single call. The model accepts text, image, audio, and video inputs natively, making it the only flagship that processes video as a first-class modality. Built on a mixture-of-experts architecture, Gemini 1.5 Pro delivers strong reasoning performance at roughly half the price of GPT-4o. It powers the Gemini Advanced consumer product, Google Cloud Vertex AI, and Google Workspace AI features. The long-context capability is particularly valuable for enterprises dealing with large legal contracts, financial filings, or research corpora.

## Key Specifications

| Attribute | Value |
|-----------|-------|
| Vendor | Google DeepMind |
| Version | 1.5-pro |
| Release Date | 2024-02-15 |
| Context Window | 2,000,000 tokens |
| Input Modalities | text, image, audio, video |
| Output Modalities | text |
| License | Proprietary |
| Documentation | https://ai.google.dev/gemini-api/docs |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|-----------|-------|------|-------|
| MMLU | 85.9 | % | 5-shot |
| HumanEval | 71.9 | pass@1 | — |
| GSM8K | 91.7 | % | 0-shot CoT |
| MATH | 58.5 | % | 0-shot CoT |
| BBH | 84.0 | % | 3-shot CoT |

## Pricing

| Tier | Price (per 1M tokens) |
|------|------------------------|
| Input | $1.25 |
| Output | $5.00 |
| Cache Read | $0.3125 |
| Cache Write | $1.25 |

Pricing source: https://ai.google.dev/pricing (as of 2024-08-01).

## Strengths

- Industry-leading 2M token context window for ultra-long inputs.
- Native video modality support, unique among flagship models.
- Competitive pricing — roughly half of GPT-4o.
- Strong multimodal grounding across text, image, audio, and video.

## Weaknesses

- HumanEval score (71.9) trails GPT-4o and Claude 3.5 Sonnet on pure coding.
- Long-context recall can be inconsistent for facts buried deep in the input.
- Proprietary model with no self-host option.

## Use Cases

- Whole-codebase refactoring and analysis.
- Long-video summarization and content moderation.
- Multi-document legal and financial research.
- Cross-modal retrieval over mixed media archives.

## References

- [Gemini 1.5 Pro — Google DeepMind](https://deepmind.google/technologies/gemini/)
- [Gemini API Pricing](https://ai.google.dev/pricing)
- [Gemini API Documentation](https://ai.google.dev/gemini-api/docs)
