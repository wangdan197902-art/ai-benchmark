---
title: "Llama 3.1 405B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Meta's Llama 3.1 405B across MMLU, HumanEval, GSM8K, MATH, and BBH benchmarks with pricing and use-hosting considerations."
date: 2024-07-23
lastmod: 2024-08-15
draft: false
weight: 40
model_id: "llama-3-1-405b"
vendor: "meta"
version: "3.1-405b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Llama 3.1 405B

## Model Overview

Llama 3.1 405B is Meta's flagship open-weights model, released on July 23, 2024. With 405 billion parameters and a 128K context window, it is the largest openly available foundation model to date. Meta reports that Llama 3.1 405B closes the gap with closed-source flagships like GPT-4o and Claude 3.5 Sonnet on MMLU, HumanEval, and MATH, enabling organizations that require full model control — for regulatory, privacy, or customization reasons — to deploy a near-frontier model on their own infrastructure. The weights are released under the Llama 3 Community License, which permits commercial use for organizations with fewer than 700 million monthly active users. The model is available via major cloud providers (AWS, Azure, Google Cloud) and self-hosted on clusters of 8× H100 GPUs or equivalent.

## Key Specifications

| Attribute | Value |
|-----------|-------|
| Vendor | Meta |
| Version | 3.1-405b |
| Release Date | 2024-07-23 |
| Context Window | 128,000 tokens |
| Input Modalities | text |
| Output Modalities | text |
| License | Llama 3 Community License |
| Documentation | https://llama.meta.com/docs/ |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|-----------|-------|------|-------|
| MMLU | 88.6 | % | 5-shot |
| HumanEval | 89.0 | pass@1 | — |
| GSM8K | 89.2 | % | 0-shot CoT |
| MATH | 73.8 | % | 0-shot CoT |
| BBH | 82.9 | % | 3-shot CoT |

## Pricing

| Tier | Price (per 1M tokens) |
|------|------------------------|
| Input (Together AI hosted) | $5.00 |
| Output (Together AI hosted) | $15.00 |
| Cache Read | $0.00 |
| Cache Write | $0.00 |

Pricing source: https://www.together.ai/pricing (as of 2024-08-01). Self-hosted pricing depends on GPU infrastructure cost.

## Strengths

- Largest open-weights model available, with near-frontier performance.
- Full model control for regulatory-sensitive industries (defense, healthcare, finance).
- Llama 3 Community License permits commercial use for most organizations.
- Mature ecosystem with vLLM, TGI, and TensorRT-LLM serving stacks.

## Weaknesses

- Requires significant GPU infrastructure (8× H100 80GB recommended) to self-host.
- No native multimodal support (text-only).
- Self-hosting introduces operational complexity for inference, scaling, and monitoring.

## Use Cases

- On-premise deployments for regulated industries.
- Custom fine-tuning and domain-specific adaptation.
- Sovereign AI initiatives requiring full data control.
- Research workloads needing weight-level access.

## References

- [Meta Llama 3.1 Announcement](https://ai.meta.com/blog/meta-llama-3-1/)
- [Llama Documentation](https://llama.meta.com/docs/)
- [Together AI Pricing](https://www.together.ai/pricing)
