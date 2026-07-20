---
title: "StableLM 2 1.6B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StableLM 2 1.6B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-19
lastmod: 2024-01-19
draft: false
weight: 10
model_id: "stablelm-2-1-6b"
vendor: "other"
version: "stablelm-2-1-6b"
tags: ["open-weights", "self-hostable"]
---

# StableLM 2 1.6B

## मॉडल अवलोकन

Stability AI StableLM 2 1.6B 轻量模型, 4K 上下文, 多语言训练, 适合移动设备部署。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | stablelm-2-1-6b | 2024-01-19 | 4K | text | text | Stability AI Community License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 52.7 | % | 5-shot |
| HumanEval | 37.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 43.5 | % | 0-shot CoT |
| MATH | 26.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 40.7 | % | 3-shot CoT |
| GPQA | 15.0 | % | 0-shot |
| IFEval | 44.1 | % | prompt_strict |
| ARC | 77.7 | % | challenge |
| MUSR | 26.4 | % | 0-shot |
| WinoGrande | 70.3 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- MMLU 仅 52.7，知识推理偏弱。
- HumanEval 37.3，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [StableLM 2 1.6B दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2024-01-19
- विक्रेता: Other
