---
title: "Qwen2.5 72B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2.5 72B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-72b"
vendor: "alibaba"
version: "2.5-72b"
tags: ["open-weights", "chinese", "coding"]
---

# Qwen2.5 72B

## 모델 개요

阿里巴巴通义千问 Qwen2.5 72B 开源模型，131K 上下文窗口，在中文理解、代码生成与数学推理上表现突出，是当前最强的中文开源模型之一。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-72b | 2024-09-19 | 131K | text | text | Qwen License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 86.1 | % | 5-shot |
| HumanEval | 86.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 88.4 | % | 0-shot CoT |
| MATH | 83.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.4 | % | 3-shot CoT |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 86.1, strong knowledge reasoning.
- HumanEval 86.6, excellent code generation.
- GSM8K 88.4, robust math reasoning.

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试

## 참고문헌

- [Qwen2.5 72B 문서](https://qwenlm.github.io/)
- 출시일: 2024-09-19
- 공급업체: Alibaba
