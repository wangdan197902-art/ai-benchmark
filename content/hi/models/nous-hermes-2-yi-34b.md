---
title: "Nous Hermes 2 Yi 34B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Nous Hermes 2 Yi 34B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-22
lastmod: 2024-01-22
draft: false
weight: 10
model_id: "nous-hermes-2-yi-34b"
vendor: "other"
version: "nous-hermes-2-yi-34b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Nous Hermes 2 Yi 34B

## मॉडल अवलोकन

NousResearch Hermes 2 Yi 34B 微调模型, 4K 上下文, 基于 Yi 34B, 改进多语言与指令遵循。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-hermes-2-yi-34b | 2024-01-22 | 4K | text | text | Apache 2.0 |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.9 | % | 5-shot |
| HumanEval | 73.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.7 | % | 0-shot CoT |
| MATH | 44.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.6 | % | 3-shot CoT |
| GPQA | 39.0 | % | 0-shot |
| IFEval | 68.3 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 48.8 | % | 0-shot |
| WinoGrande | 83.4 | % | 0-shot |

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

- 代码生成与调试

## संदर्भ

- [Nous Hermes 2 Yi 34B दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2024-01-22
- विक्रेता: Other
