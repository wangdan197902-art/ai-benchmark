---
title: "Code Llama 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Code Llama 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-29
lastmod: 2024-01-29
draft: false
weight: 10
model_id: "code-llama-70b"
vendor: "meta"
version: "code-llama-70b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Code Llama 70B

## मॉडल अवलोकन

Meta Code Llama 70B 代码专用开源模型, 16K 上下文, 基于 Llama 2 微调, 支持多语言代码生成。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | code-llama-70b | 2024-01-29 | 16K | text | text | Llama 2 Community License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 62.1 | % | 5-shot |
| HumanEval | 65.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 61.0 | % | 0-shot CoT |
| MATH | 34.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.1 | % | 3-shot CoT |
| GPQA | 25.3 | % | 0-shot |
| IFEval | 63.8 | % | prompt_strict |
| ARC | 89.8 | % | challenge |
| MUSR | 40.1 | % | 0-shot |
| WinoGrande | 75.5 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## उपयोग के मामले

- 代码生成与调试

## संदर्भ

- [Code Llama 70B दस्तावेज़ीकरण](https://llama.meta.com/docs/)
- रिलीज़ तिथि: 2024-01-29
- विक्रेता: Meta
