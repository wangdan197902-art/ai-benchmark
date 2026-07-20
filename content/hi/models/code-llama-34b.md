---
title: "Code Llama 34B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Code Llama 34B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-08-24
lastmod: 2023-08-24
draft: false
weight: 10
model_id: "code-llama-34b"
vendor: "meta"
version: "code-llama-34b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Code Llama 34B

## मॉडल अवलोकन

Meta Code Llama 34B 代码专用开源模型, 16K 上下文, 中等规模, 平衡代码生成性能与资源消耗。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | code-llama-34b | 2023-08-24 | 16K | text | text | Llama 2 Community License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 74.5 | % | 5-shot |
| HumanEval | 71.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 59.8 | % | 0-shot CoT |
| MATH | 44.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 59.1 | % | 3-shot CoT |
| GPQA | 27.0 | % | 0-shot |
| IFEval | 58.7 | % | prompt_strict |
| ARC | 88.7 | % | challenge |
| MUSR | 44.9 | % | 0-shot |
| WinoGrande | 80.0 | % | 0-shot |

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

- [Code Llama 34B दस्तावेज़ीकरण](https://llama.meta.com/docs/)
- रिलीज़ तिथि: 2023-08-24
- विक्रेता: Meta
