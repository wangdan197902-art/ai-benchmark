---
title: "OLMo 1.7 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of OLMo 1.7 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-23
lastmod: 2024-08-23
draft: false
weight: 10
model_id: "olmo-1-7-7b"
vendor: "other"
version: "olmo-1-7-7b"
tags: ["open-weights", "self-hostable"]
---

# OLMo 1.7 7B

## मॉडल अवलोकन

AllenAI OLMo 1.7 7B 第二代模型, 4K 上下文, 改进训练流程, 性能超越初代 OLMo 7B。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | olmo-1-7-7b | 2024-08-23 | 4K | text | text | Apache 2.0 |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.5 | % | 5-shot |
| HumanEval | 67.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.5 | % | 0-shot CoT |
| MATH | 38.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 68.9 | % | 3-shot CoT |
| GPQA | 26.9 | % | 0-shot |
| IFEval | 61.2 | % | prompt_strict |
| ARC | 91.8 | % | challenge |
| MUSR | 42.6 | % | 0-shot |
| WinoGrande | 76.6 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [OLMo 1.7 7B दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2024-08-23
- विक्रेता: Other
