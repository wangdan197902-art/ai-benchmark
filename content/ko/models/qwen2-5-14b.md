---
title: "Qwen2.5 14B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2.5 14B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-14b"
vendor: "alibaba"
version: "2.5-14b"
tags: ["open-weights", "chinese"]
---

# Qwen2.5 14B

## 모델 개요

阿里巴巴 Qwen2.5 14B 开源中型模型, 131K 上下文, 平衡性能与资源, 适合企业级部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-14b | 2024-09-19 | 131K | text | text | Qwen License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.4 | % | 5-shot |
| HumanEval | 72.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.0 | % | 0-shot CoT |
| MATH | 38.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.2 | % | 3-shot CoT |
| GPQA | 44.5 | % | 0-shot |
| IFEval | 74.1 | % | prompt_strict |
| ARC | 94.2 | % | challenge |
| MUSR | 50.5 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

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

- [Qwen2.5 14B 문서](https://qwenlm.github.io/)
- 출시일: 2024-09-19
- 공급업체: Alibaba
