---
title: "Code Bison: Complete Benchmark Performance Guide"
description: "In-depth analysis of Code Bison performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-05-10
lastmod: 2023-05-10
draft: false
weight: 10
model_id: "code-bison"
vendor: "google"
version: "code-bison"
tags: ["coding", "legacy"]
---

# Code Bison

## 모델 개요

Google Vertex AI Code Bison 代码生成模型, 基于 PaLM 2, 8K 上下文, 支持多语言代码生成与补全。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | code-bison | 2023-05-10 | 8K | text | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.0 | % | 5-shot |
| HumanEval | 76.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 55.0 | % | 0-shot CoT |
| MATH | 34.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.4 | % | 3-shot CoT |
| GPQA | 29.1 | % | 0-shot |
| IFEval | 59.2 | % | prompt_strict |
| ARC | 86.1 | % | challenge |
| MUSR | 49.8 | % | 0-shot |
| WinoGrande | 77.9 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## 사용 사례

- 代码生成与调试

## 참고문헌

- [Code Bison 문서](https://ai.google.dev/gemini-api/docs)
- 출시일: 2023-05-10
- 공급업체: Google
