---
title: "Llama Guard 2 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama Guard 2 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-18
lastmod: 2024-04-18
draft: false
weight: 10
model_id: "llama-guard-2-8b"
vendor: "meta"
version: "guard-2-8b"
tags: ["open-weights", "self-hostable"]
---

# Llama Guard 2 8B

## मॉडल अवलोकन

Meta Llama Guard 2 8B 内容安全分类模型, 8K 上下文, 用于检测输入输出中的有害内容。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | guard-2-8b | 2024-04-18 | 8K | text | text | Llama 3 Community License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.0 | % | 5-shot |
| HumanEval | 26.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 46.3 | % | 0-shot CoT |
| MATH | 26.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 47.6 | % | 3-shot CoT |
| GPQA | 18.0 | % | 0-shot |
| IFEval | 51.6 | % | prompt_strict |
| ARC | 76.3 | % | challenge |
| MUSR | 34.9 | % | 0-shot |
| WinoGrande | 66.5 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- MMLU 仅 51.0，知识推理偏弱。
- HumanEval 26.6，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [Llama Guard 2 8B दस्तावेज़ीकरण](https://llama.meta.com/docs/)
- रिलीज़ तिथि: 2024-04-18
- विक्रेता: Meta
