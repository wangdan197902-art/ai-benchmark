---
title: "Gemini 1.5 Pro vs Qwen2.5 72B: Benchmark Comparison"
description: "Detailed comparison of Gemini 1.5 Pro and Qwen2.5 72B covering benchmarks, pricing, context window, and compliance."
date: 2024-02-15
lastmod: 2024-02-15
draft: false
weight: 10
comparison_id: "gemini-1-5-pro-vs-qwen2-5-72b"
models: ["gemini-1-5-pro", "qwen2-5-72b"]
benchmarks: ["bbh", "gsm8k", "humaneval", "math", "mmlu"]
verdict: "See Editor's Take section."
tags: ["comparison", "google", "alibaba"]
---

# Gemini 1.5 Pro 대 Qwen2.5 72B

## 모델 개요

Gemini 1.5 Pro and Qwen2.5 72B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 핵심 사양

| 공급업체 | 출시일 | 컨텍스트 창 | 라이선스 |
|---------|-------------|----------------|---------|
| Google / Alibaba | 2024-02-15 / 2024-09-19 | 2000K / 131K | Proprietary / Qwen License |

## 벤치마크 성능

| 벤치마크 | Gemini 1.5 Pro | Qwen2.5 72B | 승자 |
|------|------|------|--------|
| BBH (BIG-Bench Hard) | 84.0 | 82.4 | A |
| GSM8K (Grade School Math 8K) | 91.7 | 88.4 | A |
| HumanEval | 71.9 | 86.6 | B |
| MATH | 58.5 | 83.1 | B |
| MMLU (Massive Multitask Language Understanding) | 85.9 | 86.1 | Tie |

## 가격 비교

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*백만 토큰당 — A / B*

## 강점 & 약점

### Gemini 1.5 Pro

- ✅ MMLU score 85.9, strong knowledge reasoning.
- ✅ GSM8K 91.7, robust math reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 2000K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

### Qwen2.5 72B

- ✅ MMLU score 86.1, strong knowledge reasoning.
- ✅ HumanEval 86.6, excellent code generation.
- ✅ GSM8K 88.4, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## 편집자 의견

Gemini 1.5 Pro and Qwen2.5 72B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 참고문헌

- [Gemini 1.5 Pro 문서](https://ai.google.dev/gemini-api/docs)
- [Qwen2.5 72B 문서](https://qwenlm.github.io/)
