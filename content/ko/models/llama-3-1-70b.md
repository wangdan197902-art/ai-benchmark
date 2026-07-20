---
title: "Llama 3.1 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.1 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-23
lastmod: 2024-07-23
draft: false
weight: 10
model_id: "llama-3-1-70b"
vendor: "meta"
version: "3.1-70b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3.1 70B

## 모델 개요

Meta Llama 3.1 70B 中端开源模型, 128K 上下文, 性能接近 GPT-4, 推理与编码能力突出。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.1-70b | 2024-07-23 | 128K | text | text | Llama 3 Community License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.6 | % | 5-shot |
| HumanEval | 79.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.8 | % | 0-shot CoT |
| MATH | 38.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.2 | % | 3-shot CoT |
| GPQA | 40.0 | % | 0-shot |
| IFEval | 73.7 | % | prompt_strict |
| ARC | 92.3 | % | challenge |
| MUSR | 48.1 | % | 0-shot |
| WinoGrande | 81.0 | % | 0-shot |

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

- [Llama 3.1 70B 문서](https://llama.meta.com/docs/)
- 출시일: 2024-07-23
- 공급업체: Meta
