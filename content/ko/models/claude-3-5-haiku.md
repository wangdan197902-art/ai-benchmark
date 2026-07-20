---
title: "Claude 3.5 Haiku: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3.5 Haiku performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-11-04
lastmod: 2024-11-04
draft: false
weight: 10
model_id: "claude-3-5-haiku"
vendor: "anthropic"
version: "3.5-haiku"
tags: ["realtime", "coding"]
---

# Claude 3.5 Haiku

## 모델 개요

Anthropic Claude 3.5 Haiku 经济型模型, 200K 上下文, 速度比 Sonnet 快 2 倍, 性能超越 Claude 3 Opus。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3.5-haiku | 2024-11-04 | 200K | text, image | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.6 | % | 5-shot |
| HumanEval | 73.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.5 | % | 0-shot CoT |
| MATH | 53.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.2 | % | 3-shot CoT |
| GPQA | 31.1 | % | 0-shot |
| IFEval | 73.6 | % | prompt_strict |
| ARC | 91.8 | % | challenge |
| MUSR | 52.3 | % | 0-shot |
| WinoGrande | 83.8 | % | 0-shot |

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

- [Claude 3.5 Haiku 문서](https://docs.anthropic.com/claude/docs)
- 출시일: 2024-11-04
- 공급업체: Anthropic
