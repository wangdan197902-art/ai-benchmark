---
title: "Claude 3 Haiku (2024-03-07): Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Haiku (2024-03-07) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-07
lastmod: 2024-03-07
draft: false
weight: 10
model_id: "claude-3-haiku-20240307"
vendor: "anthropic"
version: "3-haiku-20240307"
tags: ["realtime"]
---

# Claude 3 Haiku (2024-03-07)

## 모델 개요

Anthropic Claude 3 Haiku 2024-03-07 快照版本, 200K 上下文, 最快响应速度的经济型模型。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-haiku-20240307 | 2024-03-07 | 200K | text, image | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.1 | % | 5-shot |
| HumanEval | 74.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.5 | % | 0-shot CoT |
| MATH | 44.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.2 | % | 3-shot CoT |
| GPQA | 39.6 | % | 0-shot |
| IFEval | 75.3 | % | prompt_strict |
| ARC | 91.6 | % | challenge |
| MUSR | 51.0 | % | 0-shot |
| WinoGrande | 79.5 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试

## 참고문헌

- [Claude 3 Haiku (2024-03-07) 문서](https://docs.anthropic.com/claude/docs)
- 출시일: 2024-03-07
- 공급업체: Anthropic
