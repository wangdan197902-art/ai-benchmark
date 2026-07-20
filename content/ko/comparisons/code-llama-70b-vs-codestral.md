---
title: "Code Llama 70B vs Codestral: Benchmark Comparison"
description: "Detailed comparison of Code Llama 70B and Codestral covering benchmarks, pricing, context window, and compliance."
date: 2024-01-29
lastmod: 2024-01-29
draft: false
weight: 10
comparison_id: "code-llama-70b-vs-codestral"
models: ["code-llama-70b", "codestral"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "meta", "mistral"]
---

# Code Llama 70B 대 Codestral

## 모델 개요

Code Llama 70B and Codestral are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 핵심 사양

| 공급업체 | 출시일 | 컨텍스트 창 | 라이선스 |
|---------|-------------|----------------|---------|
| Meta / Mistral | 2024-01-29 / 2024-05-29 | 16K / 32K | Llama 2 Community License / MNPL |

## 벤치마크 성능

| 벤치마크 | Code Llama 70B | Codestral | 승자 |
|------|------|------|--------|
| ARC | 89.8 | 87.4 | A |
| BBH (BIG-Bench Hard) | 72.1 | 58.3 | A |
| GPQA | 25.3 | 32.4 | B |
| GSM8K (Grade School Math 8K) | 61.0 | 63.3 | B |
| HumanEval | 65.6 | 69.2 | B |
| IFEval | 63.8 | 59.4 | A |
| MATH | 34.0 | 29.4 | A |
| MMLU (Massive Multitask Language Understanding) | 62.1 | 75.1 | B |
| MUSR | 40.1 | 47.2 | B |
| WinoGrande | 75.5 | 75.8 | Tie |

## 가격 비교

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*백만 토큰당 — A / B*

## 강점 & 약점

### Code Llama 70B

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 16K 偏小。

### Codestral

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。

## 편집자 의견

Code Llama 70B and Codestral each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 참고문헌

- [Code Llama 70B 문서](https://llama.meta.com/docs/)
- [Codestral 문서](https://docs.mistral.ai/)
