---
title: "GPT-4o: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4o's performance across MMLU, HumanEval, GSM8K, MATH, and BBH benchmarks with pricing and use cases."
date: 2024-05-13
lastmod: 2024-08-15
draft: false
weight: 10
model_id: "gpt-4o"
vendor: "openai"
version: "4o"
tags: ["flagship", "multimodal", "openai"]
---

# GPT-4o

## Model Overview

GPT-4o is OpenAI's flagship multimodal model released on May 13, 2024. The "o" stands for omni, reflecting its native support for text, image, and audio inputs and outputs within a single neural network. With a 128K context window and optimized latency, GPT-4o is designed for real-time voice conversation, vision tasks, and high-throughput text generation. It matches or exceeds GPT-4 Turbo on academic benchmarks while being 50% cheaper and 2x faster. The model powers ChatGPT's voice mode, vision features, and the OpenAI API flagship tier, making it the default choice for general-purpose production workloads that require multimodal understanding. GPT-4o is also the first OpenAI model trained with a fully unified tokenizer across modalities, which significantly improves non-English language quality.

## Key Specifications

| Attribute | Value |
|-----------|-------|
| Vendor | OpenAI |
| Version | 4o |
| Release Date | 2024-05-13 |
| Context Window | 128,000 tokens |
| Input Modalities | text, image, audio |
| Output Modalities | text, audio |
| License | Proprietary |
| Documentation | https://platform.openai.com/docs/models/gpt-4o |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|-----------|-------|------|-------|
| MMLU | 88.7 | % | 5-shot |
| HumanEval | 90.2 | pass@1 | — |
| GSM8K | 95.8 | % | 0-shot CoT |
| MATH | 76.6 | % | 0-shot CoT |
| BBH | 83.1 | % | 3-shot CoT |

## Pricing

| Tier | Price (per 1M tokens) |
|------|------------------------|
| Input | $2.50 |
| Output | $10.00 |
| Cache Read | $1.25 |
| Cache Write | $2.50 |

Pricing source: https://openai.com/api/pricing/ (as of 2024-08-01).

## Strengths

- Native multimodal support across text, image, and audio in a single model.
- Strong reasoning and coding performance, leading on GSM8K among closed-source flagships.
- Lower latency than GPT-4 Turbo, enabling real-time voice applications.
- Robust multilingual capability thanks to the unified tokenizer.

## Weaknesses

- Closed-source proprietary model with no self-host option.
- 128K context window is smaller than Gemini 1.5 Pro (2M) and Claude 3.5 Sonnet (200K).
- Pricing is higher than open-weights competitors like DeepSeek V3 and Qwen2.5 72B.

## Use Cases

- Real-time voice assistants and conversational agents.
- Multimodal applications requiring simultaneous image and text understanding.
- Production chatbots needing low-latency responses.
- Agentic workflows that combine vision, audio, and tool calls.

## References

- [Hello GPT-4o — OpenAI](https://openai.com/index/hello-gpt-4o/)
- [OpenAI API Pricing](https://openai.com/api/pricing/)
- [GPT-4o Documentation](https://platform.openai.com/docs/models/gpt-4o)
