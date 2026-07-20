---
title: "Yi 34B vs Yi 6B: Benchmark Comparison"
description: "Detailed comparison of Yi 34B and Yi 6B covering benchmarks, pricing, context window, and compliance."
date: 2023-11-05
lastmod: 2023-11-05
draft: false
weight: 10
comparison_id: "yi-34b-vs-yi-6b"
models: ["yi-34b", "yi-6b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "other"]
---

# Yi 34B बनाम Yi 6B

## मॉडल अवलोकन

Yi 34B and Yi 6B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## मुख्य विशिष्टताएं

| विक्रेता | रिलीज़ तिथि | संदर्भ विंडो | लाइसेंस |
|---------|-------------|----------------|---------|
| Other / Other | 2023-11-05 / 2023-11-05 | 4K / 4K | Apache 2.0 / Apache 2.0 |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | Yi 34B | Yi 6B | विजेता |
|------|------|------|--------|
| ARC | 87.2 | 88.4 | B |
| BBH (BIG-Bench Hard) | 48.8 | 55.3 | B |
| GPQA | 20.6 | 26.3 | B |
| GSM8K (Grade School Math 8K) | 48.3 | 37.0 | A |
| HumanEval | 35.8 | 42.3 | B |
| IFEval | 48.2 | 54.9 | B |
| MATH | 20.5 | 29.9 | B |
| MMLU (Massive Multitask Language Understanding) | 55.5 | 68.0 | B |
| MUSR | 36.8 | 29.5 | A |
| WinoGrande | 71.5 | 72.2 | B |

## मूल्य तुलना

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*प्रति मिलियन टोकन — A / B*

## ताकत & कमजोरियां

### Yi 34B

- ✅ 可靠的通用模型。
- ⚠️ MMLU 仅 55.5，知识推理偏弱。
- ⚠️ HumanEval 35.8，代码能力较弱。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 4K 偏小。

### Yi 6B

- ✅ 可靠的通用模型。
- ⚠️ HumanEval 42.3，代码能力较弱。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 4K 偏小。

## संपादक की राय

Yi 34B and Yi 6B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## अक्सर पूछे जाने वाले प्रश्न

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## संदर्भ

- [Yi 34B दस्तावेज़ीकरण](https://huggingface.co/models)
- [Yi 6B दस्तावेज़ीकरण](https://huggingface.co/models)
