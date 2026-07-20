---
title: "Claude Instant 1: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude Instant 1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-03-14
lastmod: 2023-03-14
draft: false
weight: 10
model_id: "claude-instant-1"
vendor: "anthropic"
version: "instant-1"
tags: ["legacy"]
---

# Claude Instant 1

## मॉडल अवलोकन

Anthropic Claude Instant 1 轻量快速模型, 9K 上下文, 价格仅为 Claude 1 的 1/5, 适合实时对话。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | instant-1 | 2023-03-14 | 9K | text | text | Proprietary |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 57.1 | % | 5-shot |
| HumanEval | 28.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 34.0 | % | 0-shot CoT |
| MATH | 22.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 63.1 | % | 3-shot CoT |
| GPQA | 21.8 | % | 0-shot |
| IFEval | 53.2 | % | prompt_strict |
| ARC | 80.9 | % | challenge |
| MUSR | 33.5 | % | 0-shot |
| WinoGrande | 77.2 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- MMLU 仅 57.1，知识推理偏弱。
- HumanEval 28.5，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 9K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [Claude Instant 1 दस्तावेज़ीकरण](https://docs.anthropic.com/claude/docs)
- रिलीज़ तिथि: 2023-03-14
- विक्रेता: Anthropic
