---
title: "Claude 3 Haiku: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Haiku performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-07
lastmod: 2024-03-07
draft: false
weight: 10
model_id: "claude-3-haiku"
vendor: "anthropic"
version: "3-haiku"
tags: ["realtime"]
---

# Claude 3 Haiku

## मॉडल अवलोकन

Anthropic Claude 3 Haiku 经济型模型, 200K 上下文, 响应速度最快, 适合高吞吐量实时场景。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-haiku | 2024-03-07 | 200K | text, image | text | Proprietary |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.9 | % | 5-shot |
| HumanEval | 69.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.2 | % | 0-shot CoT |
| MATH | 52.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.7 | % | 3-shot CoT |
| GPQA | 44.4 | % | 0-shot |
| IFEval | 70.8 | % | prompt_strict |
| ARC | 94.3 | % | challenge |
| MUSR | 58.1 | % | 0-shot |
| WinoGrande | 84.8 | % | 0-shot |

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

- [Claude 3 Haiku दस्तावेज़ीकरण](https://docs.anthropic.com/claude/docs)
- रिलीज़ तिथि: 2024-03-07
- विक्रेता: Anthropic
