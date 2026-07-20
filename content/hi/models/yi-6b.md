---
title: "Yi 6B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Yi 6B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-05
lastmod: 2023-11-05
draft: false
weight: 10
model_id: "yi-6b"
vendor: "other"
version: "yi-6b"
tags: ["open-weights", "chinese", "self-hostable", "legacy"]
---

# Yi 6B

## मॉडल अवलोकन

01.AI Yi 6B 经济型首代模型, 4K 上下文, 6B 参数, 适合本地部署与研究用途。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | yi-6b | 2023-11-05 | 4K | text | text | Apache 2.0 |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 68.0 | % | 5-shot |
| HumanEval | 42.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 37.0 | % | 0-shot CoT |
| MATH | 29.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 55.3 | % | 3-shot CoT |
| GPQA | 26.3 | % | 0-shot |
| IFEval | 54.9 | % | prompt_strict |
| ARC | 88.4 | % | challenge |
| MUSR | 29.5 | % | 0-shot |
| WinoGrande | 72.2 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- HumanEval 42.3，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [Yi 6B दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2023-11-05
- विक्रेता: Other
