---
title: "Qwen2.5 3B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2.5 3B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-3b"
vendor: "alibaba"
version: "2.5-3b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Qwen2.5 3B

## मॉडल अवलोकन

阿里巴巴 Qwen2.5 3B 轻量开源模型, 32K 上下文, 3B 参数, 适合移动设备与边缘部署。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-3b | 2024-09-19 | 32K | text | text | Qwen License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 56.8 | % | 5-shot |
| HumanEval | 49.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 31.3 | % | 0-shot CoT |
| MATH | 17.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.8 | % | 3-shot CoT |
| GPQA | 18.0 | % | 0-shot |
| IFEval | 56.0 | % | prompt_strict |
| ARC | 76.5 | % | challenge |
| MUSR | 23.3 | % | 0-shot |
| WinoGrande | 61.4 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- MMLU 仅 56.8，知识推理偏弱。
- HumanEval 49.0，代码能力较弱。
- 闭源专有模型，不支持自托管。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [Qwen2.5 3B दस्तावेज़ीकरण](https://qwenlm.github.io/)
- रिलीज़ तिथि: 2024-09-19
- विक्रेता: Alibaba
