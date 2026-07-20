---
title: "ChatGLM3 6B: Complete Benchmark Performance Guide"
description: "In-depth analysis of ChatGLM3 6B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-10-27
lastmod: 2023-10-27
draft: false
weight: 10
model_id: "chatglm3-6b"
vendor: "other"
version: "chatglm3-6b"
tags: ["open-weights", "chinese", "self-hostable", "legacy"]
---

# ChatGLM3 6B

## मॉडल अवलोकन

清华智谱 ChatGLM3 6B 第三代开源模型, 32K 上下文, 6B 参数, 中英双语对话能力突出, 适合本地部署。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | chatglm3-6b | 2023-10-27 | 32K | text | text | GLM-3 License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.0 | % | 5-shot |
| HumanEval | 51.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 37.9 | % | 0-shot CoT |
| MATH | 31.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 55.7 | % | 3-shot CoT |
| GPQA | 20.1 | % | 0-shot |
| IFEval | 42.5 | % | prompt_strict |
| ARC | 88.9 | % | challenge |
| MUSR | 42.9 | % | 0-shot |
| WinoGrande | 67.7 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- MMLU 仅 58.0，知识推理偏弱。
- 闭源专有模型，不支持自托管。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [ChatGLM3 6B दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2023-10-27
- विक्रेता: Other
