---
title: "Mistral Large vs Mistral Medium: Benchmark Comparison"
description: "Detailed comparison of Mistral Large and Mistral Medium covering benchmarks, pricing, context window, and compliance."
date: 2024-02-26
lastmod: 2024-02-26
draft: false
weight: 10
comparison_id: "mistral-large-vs-mistral-medium"
models: ["mistral-large", "mistral-medium"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "mistral", "mistral"]
---

# Mistral Large 대 Mistral Medium

## 모델 개요

Mistral Large and Mistral Medium are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 핵심 사양

| 공급업체 | 출시일 | 컨텍스트 창 | 라이선스 |
|---------|-------------|----------------|---------|
| Mistral / Mistral | 2024-02-26 / 2023-12-11 | 32K / 32K | Apache 2.0 / Apache 2.0 |

## 벤치마크 성능

| 벤치마크 | Mistral Large | Mistral Medium | 승자 |
|------|------|------|--------|
| ARC | 93.3 | 94.6 | B |
| BBH (BIG-Bench Hard) | 76.7 | 83.4 | B |
| GPQA | 38.1 | 48.7 | B |
| GSM8K (Grade School Math 8K) | 80.9 | 82.5 | B |
| HumanEval | 73.4 | 78.0 | B |
| IFEval | 75.8 | 77.4 | B |
| MATH | 49.3 | 54.9 | B |
| MMLU (Massive Multitask Language Understanding) | 82.0 | 82.9 | B |
| MUSR | 52.1 | 64.3 | B |
| WinoGrande | 83.3 | 82.4 | A |

## 가격 비교

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*백만 토큰당 — A / B*

## 강점 & 약점

### Mistral Large

- ✅ MMLU score 82.0, strong knowledge reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### Mistral Medium

- ✅ MMLU score 82.9, strong knowledge reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## 편집자 의견

Mistral Large and Mistral Medium each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 참고문헌

- [Mistral Large 문서](https://docs.mistral.ai/)
- [Mistral Medium 문서](https://docs.mistral.ai/)
