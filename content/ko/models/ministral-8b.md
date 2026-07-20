---
title: "Ministral 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Ministral 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-16
lastmod: 2024-10-16
draft: false
weight: 10
model_id: "ministral-8b"
vendor: "mistral"
version: "ministral-8b"
tags: ["open-weights", "self-hostable", "long-context"]
---

# Ministral 8B

## 모델 개요

Mistral Ministral 8B 边缘模型, 128K 上下文, 8B 参数, 为本地与边缘计算优化, 性能超越 Llama 3 8B。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | ministral-8b | 2024-10-16 | 128K | text | text | Mistral Research License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.9 | % | 5-shot |
| HumanEval | 63.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.7 | % | 0-shot CoT |
| MATH | 39.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.0 | % | 3-shot CoT |
| GPQA | 35.1 | % | 0-shot |
| IFEval | 56.1 | % | prompt_strict |
| ARC | 85.5 | % | challenge |
| MUSR | 37.0 | % | 0-shot |
| WinoGrande | 75.3 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 上下文窗口 128K，支持长文本。

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 长文档摘要

## 참고문헌

- [Ministral 8B 문서](https://docs.mistral.ai/)
- 출시일: 2024-10-16
- 공급업체: Mistral
