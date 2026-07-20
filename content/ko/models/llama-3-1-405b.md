---
title: "Llama 3.1 405B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.1 405B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-23
lastmod: 2024-07-23
draft: false
weight: 10
model_id: "llama-3-1-405b"
vendor: "meta"
version: "3.1-405b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Llama 3.1 405B

## 모델 개요

Meta Llama 3.1 405B 是当前最大规模的开源权重模型之一，拥有 4050 亿参数，128K 上下文窗口，在 MMLU、HumanEval、MATH 等基准上接近闭源旗舰水平，支持自托管部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.1-405b | 2024-07-23 | 128K | text | text | Llama 3 Community License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 88.6 | % | 5-shot |
| HumanEval | 89.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 89.2 | % | 0-shot CoT |
| MATH | 73.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.9 | % | 3-shot CoT |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 88.6, strong knowledge reasoning.
- HumanEval 89.0, excellent code generation.
- GSM8K 89.2, robust math reasoning.

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试

## 참고문헌

- [Llama 3.1 405B 문서](https://llama.meta.com/docs/)
- 출시일: 2024-07-23
- 공급업체: Meta
