---
title: "Qwen1.5 32B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen1.5 32B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-25
lastmod: 2024-02-25
draft: false
weight: 10
model_id: "qwen1-5-32b"
vendor: "alibaba"
version: "1.5-32b"
tags: ["open-weights", "chinese"]
---

# Qwen1.5 32B

## 모델 개요

阿里巴巴 Qwen1.5 32B 中端开源模型, 32K 上下文, 性能接近 72B, 适合中等规模部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 1.5-32b | 2024-02-25 | 32K | text | text | Qwen License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.9 | % | 5-shot |
| HumanEval | 77.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 81.1 | % | 0-shot CoT |
| MATH | 46.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 73.0 | % | 3-shot CoT |
| GPQA | 30.6 | % | 0-shot |
| IFEval | 68.2 | % | prompt_strict |
| ARC | 91.4 | % | challenge |
| MUSR | 54.5 | % | 0-shot |
| WinoGrande | 79.6 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 81.9, strong knowledge reasoning.

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试

## 참고문헌

- [Qwen1.5 32B 문서](https://qwenlm.github.io/)
- 출시일: 2024-02-25
- 공급업체: Alibaba
