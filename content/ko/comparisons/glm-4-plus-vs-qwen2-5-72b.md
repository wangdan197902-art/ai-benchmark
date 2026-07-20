---
title: "GLM-4 Plus vs Qwen2.5 72B: Benchmark Comparison"
description: "Detailed comparison of GLM-4 Plus and Qwen2.5 72B covering benchmarks, pricing, context window, and compliance."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
comparison_id: "glm-4-plus-vs-qwen2-5-72b"
models: ["glm-4-plus", "qwen2-5-72b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "alibaba"]
---

# GLM-4 Plus 대 Qwen2.5 72B

## 모델 개요

GLM-4 Plus and Qwen2.5 72B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 핵심 사양

| 공급업체 | 출시일 | 컨텍스트 창 | 라이선스 |
|---------|-------------|----------------|---------|
| Other / Alibaba | 2024-08-12 / 2024-09-19 | 131K / 131K | Proprietary / Qwen License |

## 벤치마크 성능

| 벤치마크 | GLM-4 Plus | Qwen2.5 72B | 승자 |
|------|------|------|--------|
| ARC | 94.5 | — | A |
| BBH (BIG-Bench Hard) | 83.6 | 82.4 | A |
| GPQA | 35.4 | — | A |
| GSM8K (Grade School Math 8K) | 81.8 | 88.4 | B |
| HumanEval | 72.7 | 86.6 | B |
| IFEval | 79.2 | — | A |
| MATH | 53.3 | 83.1 | B |
| MMLU (Massive Multitask Language Understanding) | 84.3 | 86.1 | B |
| MUSR | 51.3 | — | A |
| WinoGrande | 85.8 | — | A |

## 가격 비교

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*백만 토큰당 — A / B*

## 강점 & 약점

### GLM-4 Plus

- ✅ MMLU score 84.3, strong knowledge reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ⚠️ 闭源专有模型，不支持自托管。

### Qwen2.5 72B

- ✅ MMLU score 86.1, strong knowledge reasoning.
- ✅ HumanEval 86.6, excellent code generation.
- ✅ GSM8K 88.4, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## 편집자 의견

GLM-4 Plus and Qwen2.5 72B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 참고문헌

- [GLM-4 Plus 문서](https://huggingface.co/models)
- [Qwen2.5 72B 문서](https://qwenlm.github.io/)
