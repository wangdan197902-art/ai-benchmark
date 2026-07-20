---
title: "Llama 2 13B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 2 13B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-07-18
lastmod: 2023-07-18
draft: false
weight: 10
model_id: "llama-2-13b"
vendor: "meta"
version: "2-13b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Llama 2 13B

## मॉडल अवलोकन

Meta Llama 2 13B 中型开源模型, 4K 上下文, 13B 参数, 平衡性能与资源消耗, 适合中等规模部署。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 2-13b | 2023-07-18 | 4K | text | text | Llama 2 Community License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 56.4 | % | 5-shot |
| HumanEval | 40.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 34.6 | % | 0-shot CoT |
| MATH | 25.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.1 | % | 3-shot CoT |
| GPQA | 22.3 | % | 0-shot |
| IFEval | 49.9 | % | prompt_strict |
| ARC | 89.5 | % | challenge |
| MUSR | 33.8 | % | 0-shot |
| WinoGrande | 76.4 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- MMLU 仅 56.4，知识推理偏弱。
- HumanEval 40.7，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [Llama 2 13B दस्तावेज़ीकरण](https://llama.meta.com/docs/)
- रिलीज़ तिथि: 2023-07-18
- विक्रेता: Meta
