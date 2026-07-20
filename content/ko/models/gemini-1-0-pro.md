---
title: "Gemini 1.0 Pro: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.0 Pro performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-06
lastmod: 2023-12-06
draft: false
weight: 10
model_id: "gemini-1-0-pro"
vendor: "google"
version: "1.0-pro"
tags: ["legacy"]
---

# Gemini 1.0 Pro

## 모델 개요

Google Gemini 1.0 Pro 首代模型, 32K 上下文, 在 MMLU/GSM8K 上超越 GPT-3.5, 多模态能力初步集成。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.0-pro | 2023-12-06 | 32K | text | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.5 | % | 5-shot |
| HumanEval | 76.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.4 | % | 0-shot CoT |
| MATH | 58.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.1 | % | 3-shot CoT |
| GPQA | 47.7 | % | 0-shot |
| IFEval | 75.1 | % | prompt_strict |
| ARC | 94.1 | % | challenge |
| MUSR | 57.8 | % | 0-shot |
| WinoGrande | 84.5 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 84.5, strong knowledge reasoning.

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试

## 참고문헌

- [Gemini 1.0 Pro 문서](https://ai.google.dev/gemini-api/docs)
- 출시일: 2023-12-06
- 공급업체: Google
