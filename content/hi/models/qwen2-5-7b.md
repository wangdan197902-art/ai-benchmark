---
title: "Qwen2.5 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2.5 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-7b"
vendor: "alibaba"
version: "2.5-7b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Qwen2.5 7B

## मॉडल अवलोकन

阿里巴巴 Qwen2.5 7B 经济型开源模型, 131K 上下文, 7B 参数, 性能超越 Llama 3 8B, 适合本地部署。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-7b | 2024-09-19 | 131K | text | text | Qwen License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 73.6 | % | 5-shot |
| HumanEval | 66.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.7 | % | 0-shot CoT |
| MATH | 41.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 61.9 | % | 3-shot CoT |
| GPQA | 28.5 | % | 0-shot |
| IFEval | 55.4 | % | prompt_strict |
| ARC | 88.4 | % | challenge |
| MUSR | 46.9 | % | 0-shot |
| WinoGrande | 71.4 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- 闭源专有模型，不支持自托管。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [Qwen2.5 7B दस्तावेज़ीकरण](https://qwenlm.github.io/)
- रिलीज़ तिथि: 2024-09-19
- विक्रेता: Alibaba
