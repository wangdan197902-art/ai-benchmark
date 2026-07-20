---
title: "Mistral 7B v0.1: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral 7B v0.1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-27
lastmod: 2023-09-27
draft: false
weight: 10
model_id: "mistral-7b-v0.1"
vendor: "mistral"
version: "7b-v0.1"
tags: ["open-weights", "self-hostable"]
---

# Mistral 7B v0.1

## मॉडल अवलोकन

Mistral 7B v0.1 首版开源模型, 8K 上下文, 7B 参数, 在所有 7B 模型中表现领先, Apache 2.0 可商用。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 7b-v0.1 | 2023-09-27 | 8K | text | text | Apache 2.0 |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 68.4 | % | 5-shot |
| HumanEval | 56.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.1 | % | 0-shot CoT |
| MATH | 26.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.4 | % | 3-shot CoT |
| GPQA | 25.3 | % | 0-shot |
| IFEval | 58.9 | % | prompt_strict |
| ARC | 88.7 | % | challenge |
| MUSR | 37.4 | % | 0-shot |
| WinoGrande | 79.6 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [Mistral 7B v0.1 दस्तावेज़ीकरण](https://docs.mistral.ai/)
- रिलीज़ तिथि: 2023-09-27
- विक्रेता: Mistral
