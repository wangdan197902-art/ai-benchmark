---
title: "Nous Capybara 34B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Nous Capybara 34B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-15
lastmod: 2023-11-15
draft: false
weight: 10
model_id: "nous-capybara-34b"
vendor: "other"
version: "nous-capybara-34b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Nous Capybara 34B

## मॉडल अवलोकन

NousResearch Capybara 34B 对话模型, 4K 上下文, 基于 Yi 34B 微调, 改进长对话与推理能力。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-capybara-34b | 2023-11-15 | 4K | text | text | Apache 2.0 |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 53.2 | % | 5-shot |
| HumanEval | 50.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 31.9 | % | 0-shot CoT |
| MATH | 23.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 56.1 | % | 3-shot CoT |
| GPQA | 29.7 | % | 0-shot |
| IFEval | 52.9 | % | prompt_strict |
| ARC | 80.7 | % | challenge |
| MUSR | 31.7 | % | 0-shot |
| WinoGrande | 67.3 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- MMLU 仅 53.2，知识推理偏弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [Nous Capybara 34B दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2023-11-15
- विक्रेता: Other
