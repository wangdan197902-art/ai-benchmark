---
title: "Falcon 40B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Falcon 40B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-05-25
lastmod: 2023-05-25
draft: false
weight: 10
model_id: "falcon-40b"
vendor: "other"
version: "falcon-40b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Falcon 40B

## मॉडल अवलोकन

TII Falcon 40B 中型开源模型, 2K 上下文, 400 亿参数, 在 40B 规模上曾领先 Llama 2 70B。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | falcon-40b | 2023-05-25 | 2K | text | text | TII Falcon LLM License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 56.7 | % | 5-shot |
| HumanEval | 39.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 61.3 | % | 0-shot CoT |
| MATH | 21.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.6 | % | 3-shot CoT |
| GPQA | 21.1 | % | 0-shot |
| IFEval | 57.2 | % | prompt_strict |
| ARC | 82.9 | % | challenge |
| MUSR | 38.1 | % | 0-shot |
| WinoGrande | 65.6 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- MMLU 仅 56.7，知识推理偏弱。
- HumanEval 39.7，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [Falcon 40B दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2023-05-25
- विक्रेता: Other
