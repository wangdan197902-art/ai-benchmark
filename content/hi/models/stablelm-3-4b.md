---
title: "StableLM 3 4B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StableLM 3 4B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-26
lastmod: 2024-06-26
draft: false
weight: 10
model_id: "stablelm-3-4b"
vendor: "other"
version: "stablelm-3-4b"
tags: ["open-weights", "self-hostable"]
---

# StableLM 3 4B

## मॉडल अवलोकन

Stability AI StableLM 3 4B 模型, 4K 上下文, 多语言 (English/Spanish/German/Italian/French)。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | stablelm-3-4b | 2024-06-26 | 4K | text | text | Stability AI Community License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 50.6 | % | 5-shot |
| HumanEval | 32.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 48.1 | % | 0-shot CoT |
| MATH | 11.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 54.9 | % | 3-shot CoT |
| GPQA | 26.8 | % | 0-shot |
| IFEval | 51.6 | % | prompt_strict |
| ARC | 86.8 | % | challenge |
| MUSR | 36.6 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- MMLU 仅 50.6，知识推理偏弱。
- HumanEval 32.6，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [StableLM 3 4B दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2024-06-26
- विक्रेता: Other
