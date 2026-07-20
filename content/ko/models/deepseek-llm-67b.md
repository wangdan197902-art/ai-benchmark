---
title: "DeepSeek LLM 67B: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek LLM 67B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-05
lastmod: 2024-01-05
draft: false
weight: 10
model_id: "deepseek-llm-67b"
vendor: "deepseek"
version: "llm-67b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# DeepSeek LLM 67B

## 모델 개요

DeepSeek LLM 67B 通用开源模型, 32K 上下文, 中英文能力平衡, 在开源 67B 模型中表现突出。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | llm-67b | 2024-01-05 | 32K | text | text | DeepSeek License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.2 | % | 5-shot |
| HumanEval | 68.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.9 | % | 0-shot CoT |
| MATH | 39.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.6 | % | 3-shot CoT |
| GPQA | 37.3 | % | 0-shot |
| IFEval | 76.8 | % | prompt_strict |
| ARC | 94.0 | % | challenge |
| MUSR | 51.9 | % | 0-shot |
| WinoGrande | 78.1 | % | 0-shot |

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

- 通用对话与问答

## 참고문헌

- [DeepSeek LLM 67B 문서](https://api-docs.deepseek.com/)
- 출시일: 2024-01-05
- 공급업체: Deepseek
