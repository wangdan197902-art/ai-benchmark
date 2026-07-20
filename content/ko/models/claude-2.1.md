---
title: "Claude 2.1: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 2.1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-21
lastmod: 2023-11-21
draft: false
weight: 10
model_id: "claude-2.1"
vendor: "anthropic"
version: "2.1"
tags: ["legacy", "long-context"]
---

# Claude 2.1

## 모델 개요

Anthropic Claude 2.1, 200K 上下文, 相比 2.0 减少 2 倍幻觉率, 改进长文档召回能力。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 2.1 | 2023-11-21 | 200K | text | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 60.9 | % | 5-shot |
| HumanEval | 28.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 45.7 | % | 0-shot CoT |
| MATH | 15.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 63.8 | % | 3-shot CoT |
| GPQA | 26.4 | % | 0-shot |
| IFEval | 55.0 | % | prompt_strict |
| ARC | 84.8 | % | challenge |
| MUSR | 37.7 | % | 0-shot |
| WinoGrande | 67.4 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 上下文窗口 200K，支持长文本。

## 약점

- HumanEval 28.1，代码能力较弱。
- 闭源专有模型，不支持自托管。

## 사용 사례

- 长文档摘要

## 참고문헌

- [Claude 2.1 문서](https://docs.anthropic.com/claude/docs)
- 출시일: 2023-11-21
- 공급업체: Anthropic
