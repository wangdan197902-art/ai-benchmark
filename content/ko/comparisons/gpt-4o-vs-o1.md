---
title: "GPT-4o vs o1: Benchmark Comparison"
description: "Detailed comparison of GPT-4o and o1 covering benchmarks, pricing, context window, and compliance."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
comparison_id: "gpt-4o-vs-o1"
models: ["gpt-4o", "o1"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "openai"]
---

# GPT-4o 대 o1

## 모델 개요

GPT-4o and o1 are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 핵심 사양

| 공급업체 | 출시일 | 컨텍스트 창 | 라이선스 |
|---------|-------------|----------------|---------|
| Openai / Openai | 2024-05-13 / 2024-12-17 | 128K / 200K | Proprietary / Proprietary |

## 벤치마크 성능

| 벤치마크 | GPT-4o | o1 | 승자 |
|------|------|------|--------|
| ARC | — | 96.8 | B |
| BBH (BIG-Bench Hard) | 83.1 | 83.1 | Tie |
| GPQA | — | 57.5 | B |
| GSM8K (Grade School Math 8K) | 95.8 | 88.9 | A |
| HumanEval | 90.2 | 85.3 | A |
| IFEval | — | 82.2 | B |
| MATH | 76.6 | 55.7 | A |
| MMLU (Massive Multitask Language Understanding) | 88.7 | 86.3 | A |
| MUSR | — | 71.8 | B |
| WinoGrande | — | 86.7 | B |

## 가격 비교

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*백만 토큰당 — A / B*

## 강점 & 약점

### GPT-4o

- ✅ MMLU score 88.7, strong knowledge reasoning.
- ✅ HumanEval 90.2, excellent code generation.
- ✅ GSM8K 95.8, robust math reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ⚠️ 闭源专有模型，不支持自托管。

### o1

- ✅ MMLU score 86.3, strong knowledge reasoning.
- ✅ HumanEval 85.3, excellent code generation.
- ✅ GSM8K 88.9, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## 편집자 의견

GPT-4o and o1 each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 참고문헌

- [GPT-4o 문서](https://platform.openai.com/docs/models/gpt-4o)
- [o1 문서](https://platform.openai.com/docs/models)
