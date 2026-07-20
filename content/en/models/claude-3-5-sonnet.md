---
title: "Claude 3.5 Sonnet: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3.5 Sonnet's performance across MMLU, HumanEval, GSM8K, MATH, and BBH benchmarks with pricing and use cases."
date: 2024-06-20
lastmod: 2024-08-15
draft: false
weight: 20
model_id: "claude-3-5-sonnet"
vendor: "anthropic"
version: "3.5-sonnet"
tags: ["flagship", "coding", "long-context"]
---

# Claude 3.5 Sonnet

## Model Overview

Claude 3.5 Sonnet is Anthropic's mid-2024 flagship, released on June 20, 2024. It raises the bar on coding, vision reasoning, and long-document understanding while maintaining a 200K context window. Despite being positioned as the "mid-tier" model in the Claude 3.5 family, Sonnet outperforms the previous Claude 3 Opus on nearly every academic benchmark and operates at twice the speed. Anthropic emphasizes Constitutional AI alignment, predictable behavior, and a strong preference for enterprise use cases involving complex tool use and agentic workflows. Claude 3.5 Sonnet is also the first model to ship with the Artifacts feature in the Claude.ai web UI, allowing interactive code and content generation alongside the conversation thread.

## Key Specifications

| Attribute | Value |
|-----------|-------|
| Vendor | Anthropic |
| Version | 3.5-sonnet |
| Release Date | 2024-06-20 |
| Context Window | 200,000 tokens |
| Input Modalities | text, image |
| Output Modalities | text |
| License | Proprietary |
| Documentation | https://docs.anthropic.com/claude/docs |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|-----------|-------|------|-------|
| MMLU | 88.7 | % | 5-shot |
| HumanEval | 92.0 | pass@1 | — |
| GSM8K | 96.4 | % | 0-shot CoT |
| MATH | 71.1 | % | 0-shot CoT |
| BBH | 84.5 | % | 3-shot CoT |

## Pricing

| Tier | Price (per 1M tokens) |
|------|------------------------|
| Input | $3.00 |
| Output | $15.00 |
| Cache Read | $0.30 |
| Cache Write | $3.75 |

Pricing source: https://www.anthropic.com/pricing (as of 2024-08-01).

## Strengths

- Industry-leading HumanEval score (92.0 pass@1), making it the top choice for code generation.
- Generous 200K context window for long-document analysis and codebase reasoning.
- Vision input support for charts, screenshots, and document understanding.
- Strong tool-use and agentic workflow reliability.

## Weaknesses

- No audio modality support (text and image input only).
- Pricing is 20-50% higher than GPT-4o for input tokens.
- No self-host option; only available via Anthropic API or cloud partners.

## Use Cases

- Production code generation and refactoring.
- Long-document summarization and legal/financial analysis.
- Multimodal reasoning over mixed text+image inputs.
- Agentic automation involving tool calls and structured outputs.

## References

- [Claude 3.5 Sonnet Announcement — Anthropic](https://www.anthropic.com/news/claude-3-5-sonnet)
- [Anthropic Pricing](https://www.anthropic.com/pricing)
- [Claude Documentation](https://docs.anthropic.com/claude/docs)
