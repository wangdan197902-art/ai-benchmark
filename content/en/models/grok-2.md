---
title: "Grok-2: Complete Benchmark Performance Guide"
description: "In-depth analysis of xAI's Grok-2 across MMLU, HumanEval, GSM8K, MATH, and BBH benchmarks with pricing and real-time information considerations."
date: 2024-08-13
lastmod: 2024-08-15
draft: false
weight: 100
model_id: "grok-2"
vendor: "xai"
version: "2"
tags: ["flagship", "multimodal", "realtime"]
---

# Grok-2

## Model Overview

Grok-2 is xAI's flagship model, released on August 13, 2024. The model is notable for its tight integration with the X (formerly Twitter) platform, providing real-time awareness of current events and trending topics — a capability no other flagship model matches. Grok-2 accepts both text and image inputs, supports a 131K context window, and is positioned as a competitive alternative to GPT-4o and Claude 3.5 Sonnet on academic benchmarks. On MMLU, Grok-2 scores 87.5, within striking distance of GPT-4o (88.7) and Claude 3.5 Sonnet (88.7). The model is available via the X platform's Grok chatbot (for Premium subscribers) and the xAI API. Grok-2 is also notable for its relatively permissive content policy compared to other flagship models, which xAI positions as a feature for users seeking fewer refusals.

## Key Specifications

| Attribute | Value |
|-----------|-------|
| Vendor | xAI |
| Version | 2 |
| Release Date | 2024-08-13 |
| Context Window | 131,072 tokens |
| Input Modalities | text, image |
| Output Modalities | text |
| License | Proprietary |
| Documentation | https://docs.x.ai/ |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|-----------|-------|------|-------|
| MMLU | 87.5 | % | 5-shot |
| HumanEval | 88.4 | pass@1 | — |
| GSM8K | 93.2 | % | 0-shot CoT |
| MATH | 76.8 | % | 0-shot CoT |
| BBH | 84.0 | % | 3-shot CoT |

## Pricing

| Tier | Price (per 1M tokens) |
|------|------------------------|
| Input | $2.00 |
| Output | $10.00 |
| Cache Read | $0.00 |
| Cache Write | $0.00 |

Pricing source: https://x.ai/api (as of 2024-08-13).

## Strengths

- Real-time awareness via X platform integration, unique among flagships.
- Strong benchmark performance, competitive with GPT-4o on most metrics.
- Multimodal input (text + image) support.
- More permissive content policy for users seeking fewer refusals.

## Weaknesses

- Proprietary model with no self-host option and limited enterprise compliance certifications.
- No audio modality, unlike GPT-4o.
- Tightly coupled to the X ecosystem, which may be a concern for some enterprise buyers.
- Limited track record vs established vendors like OpenAI and Anthropic.

## Use Cases

- Real-time news and event-aware chatbots.
- Social media content generation and trend analysis.
- Customer-facing applications where current events matter.
- Image-based question answering in conjunction with text.

## References

- [Grok-2 Announcement — xAI](https://x.ai/blog/grok-2)
- [xAI API Documentation](https://docs.x.ai/)
- [xAI API Pricing](https://x.ai/api)
