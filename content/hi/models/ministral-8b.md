---
title: "Ministral 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Ministral 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-16
lastmod: 2024-10-16
draft: false
weight: 10
model_id: "ministral-8b"
vendor: "mistral"
version: "ministral-8b"
tags: ["open-weights", "self-hostable", "long-context"]
---

# Ministral 8B

## मॉडल अवलोकन

Mistral Ministral 8B 边缘模型, 128K 上下文, 8B 参数, 为本地与边缘计算优化, 性能超越 Llama 3 8B。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | ministral-8b | 2024-10-16 | 128K | text | text | Mistral Research License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.9 | % | 5-shot |
| HumanEval | 63.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.7 | % | 0-shot CoT |
| MATH | 39.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.0 | % | 3-shot CoT |
| GPQA | 35.1 | % | 0-shot |
| IFEval | 56.1 | % | prompt_strict |
| ARC | 85.5 | % | challenge |
| MUSR | 37.0 | % | 0-shot |
| WinoGrande | 75.3 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 上下文窗口 128K，支持长文本。

## कमजोरियां

- 闭源专有模型，不支持自托管。

## उपयोग के मामले

- 长文档摘要

## संदर्भ

- [Ministral 8B दस्तावेज़ीकरण](https://docs.mistral.ai/)
- रिलीज़ तिथि: 2024-10-16
- विक्रेता: Mistral
