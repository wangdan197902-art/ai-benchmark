---
title: "GPT-3.5 Turbo: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-3.5 Turbo performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-03-01
lastmod: 2023-03-01
draft: false
weight: 10
model_id: "gpt-3.5-turbo"
vendor: "openai"
version: "3.5-turbo"
tags: ["legacy", "realtime"]
---

# GPT-3.5 Turbo

## 모델 개요

OpenAI GPT-3.5 Turbo 经济型模型, 16K 上下文, 速度快价格低, 适合对话与通用任务。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 3.5-turbo | 2023-03-01 | 16K | text | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 61.1 | % | 5-shot |
| HumanEval | 51.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 34.3 | % | 0-shot CoT |
| MATH | 17.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.2 | % | 3-shot CoT |
| GPQA | 22.4 | % | 0-shot |
| IFEval | 57.4 | % | prompt_strict |
| ARC | 86.8 | % | challenge |
| MUSR | 29.2 | % | 0-shot |
| WinoGrande | 76.7 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [GPT-3.5 Turbo 문서](https://platform.openai.com/docs/models)
- 출시일: 2023-03-01
- 공급업체: Openai
