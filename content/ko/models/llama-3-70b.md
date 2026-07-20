---
title: "Llama 3 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-18
lastmod: 2024-04-18
draft: false
weight: 10
model_id: "llama-3-70b"
vendor: "meta"
version: "3-70b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3 70B

## 모델 개요

Meta Llama 3 70B 中端开源模型, 8K 上下文, 在 MMLU/HumanEval 上接近 GPT-4, 开源旗舰之一。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3-70b | 2024-04-18 | 8K | text | text | Llama 3 Community License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.5 | % | 5-shot |
| HumanEval | 73.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 76.2 | % | 0-shot CoT |
| MATH | 50.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 77.6 | % | 3-shot CoT |
| GPQA | 38.2 | % | 0-shot |
| IFEval | 72.2 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 51.2 | % | 0-shot |
| WinoGrande | 79.2 | % | 0-shot |

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

- [Llama 3 70B 문서](https://llama.meta.com/docs/)
- 출시일: 2024-04-18
- 공급업체: Meta
