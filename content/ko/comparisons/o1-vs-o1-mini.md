---
title: "o1 vs o1 mini: Benchmark Comparison"
description: "Detailed comparison of o1 and o1 mini covering benchmarks, pricing, context window, and compliance."
date: 2024-12-17
lastmod: 2024-12-17
draft: false
weight: 10
comparison_id: "o1-vs-o1-mini"
models: ["o1", "o1-mini"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "openai"]
---

# o1 대 o1 mini

## 모델 개요

o1 and o1 mini are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 핵심 사양

| 공급업체 | 출시일 | 컨텍스트 창 | 라이선스 |
|---------|-------------|----------------|---------|
| Openai / Openai | 2024-12-17 / 2024-09-12 | 200K / 128K | Proprietary / Proprietary |

## 벤치마크 성능

| 벤치마크 | o1 | o1 mini | 승자 |
|------|------|------|--------|
| ARC | 96.8 | 93.7 | A |
| BBH (BIG-Bench Hard) | 83.1 | 77.2 | A |
| GPQA | 57.5 | 40.8 | A |
| GSM8K (Grade School Math 8K) | 88.9 | 86.6 | A |
| HumanEval | 85.3 | 78.0 | A |
| IFEval | 82.2 | 73.1 | A |
| MATH | 55.7 | 44.2 | A |
| MMLU (Massive Multitask Language Understanding) | 86.3 | 78.2 | A |
| MUSR | 71.8 | 54.0 | A |
| WinoGrande | 86.7 | 78.3 | A |

## 가격 비교

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*백만 토큰당 — A / B*

## 강점 & 약점

### o1

- ✅ MMLU score 86.3, strong knowledge reasoning.
- ✅ HumanEval 85.3, excellent code generation.
- ✅ GSM8K 88.9, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### o1 mini

- ✅ GSM8K 86.6, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## 편집자 의견

o1 and o1 mini each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 참고문헌

- [o1 문서](https://platform.openai.com/docs/models)
- [o1 mini 문서](https://platform.openai.com/docs/models)
