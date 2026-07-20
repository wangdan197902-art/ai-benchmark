---
title: "Nous Hermes 2 Solar 10.7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Nous Hermes 2 Solar 10.7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-19
lastmod: 2024-02-19
draft: false
weight: 10
model_id: "nous-hermes-2-solar-10-7b"
vendor: "other"
version: "nous-hermes-2-solar-10-7b"
tags: ["open-weights", "self-hostable"]
---

# Nous Hermes 2 Solar 10.7B

## मॉडल अवलोकन

NousResearch Hermes 2 Solar 10.7B 微调模型, 4K 上下文, 基于 Solar 10.7B, 性能接近 Llama 2 70B。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-hermes-2-solar-10-7b | 2024-02-19 | 4K | text | text | Apache 2.0 |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 63.4 | % | 5-shot |
| HumanEval | 59.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 59.6 | % | 0-shot CoT |
| MATH | 37.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.8 | % | 3-shot CoT |
| GPQA | 35.9 | % | 0-shot |
| IFEval | 55.6 | % | prompt_strict |
| ARC | 85.9 | % | challenge |
| MUSR | 39.6 | % | 0-shot |
| WinoGrande | 74.4 | % | 0-shot |

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

- [Nous Hermes 2 Solar 10.7B दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2024-02-19
- विक्रेता: Other
