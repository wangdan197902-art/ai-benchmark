---
title: "Llama 2 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 2 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-07-18
lastmod: 2023-07-18
draft: false
weight: 10
model_id: "llama-2-7b"
vendor: "meta"
version: "2-7b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Llama 2 7B

## मॉडल अवलोकन

Meta Llama 2 7B 经济型开源模型, 4K 上下文, 7B 参数, 广泛用于本地部署与微调基座。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 2-7b | 2023-07-18 | 4K | text | text | Llama 2 Community License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 70.8 | % | 5-shot |
| HumanEval | 42.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 31.0 | % | 0-shot CoT |
| MATH | 19.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 54.7 | % | 3-shot CoT |
| GPQA | 23.1 | % | 0-shot |
| IFEval | 58.5 | % | prompt_strict |
| ARC | 86.5 | % | challenge |
| MUSR | 35.3 | % | 0-shot |
| WinoGrande | 77.2 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- HumanEval 42.6，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [Llama 2 7B दस्तावेज़ीकरण](https://llama.meta.com/docs/)
- रिलीज़ तिथि: 2023-07-18
- विक्रेता: Meta
