---
title: "Llama 3.1 405B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.1 405B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-23
lastmod: 2024-07-23
draft: false
weight: 10
model_id: "llama-3-1-405b"
vendor: "meta"
version: "3.1-405b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Llama 3.1 405B

## मॉडल अवलोकन

Meta Llama 3.1 405B 是当前最大规模的开源权重模型之一，拥有 4050 亿参数，128K 上下文窗口，在 MMLU、HumanEval、MATH 等基准上接近闭源旗舰水平，支持自托管部署。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.1-405b | 2024-07-23 | 128K | text | text | Llama 3 Community License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 88.6 | % | 5-shot |
| HumanEval | 89.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 89.2 | % | 0-shot CoT |
| MATH | 73.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.9 | % | 3-shot CoT |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- MMLU score 88.6, strong knowledge reasoning.
- HumanEval 89.0, excellent code generation.
- GSM8K 89.2, robust math reasoning.

## कमजोरियां

- 闭源专有模型，不支持自托管。

## उपयोग के मामले

- 代码生成与调试

## संदर्भ

- [Llama 3.1 405B दस्तावेज़ीकरण](https://llama.meta.com/docs/)
- रिलीज़ तिथि: 2024-07-23
- विक्रेता: Meta
