---
title: "Command R+ (08-2024): Complete Benchmark Performance Guide"
description: "In-depth analysis of Command R+ (08-2024) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "command-r-plus-08-2024"
vendor: "cohere"
version: "r-plus-08-2024"
tags: ["rag", "enterprise", "tool-use"]
---

# Command R+ (08-2024)

## 모델 개요

Cohere Command R+ 08-2024 版本, 128K 上下文, 改进代码生成与多语言能力, 性能接近 GPT-4。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | r-plus-08-2024 | 2024-08-13 | 128K | text | text | CC-BY-NC-4.0 |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.3 | % | 5-shot |
| HumanEval | 75.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 80.8 | % | 0-shot CoT |
| MATH | 43.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.1 | % | 3-shot CoT |
| GPQA | 38.7 | % | 0-shot |
| IFEval | 72.1 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 51.1 | % | 0-shot |
| WinoGrande | 83.4 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 82.3, strong knowledge reasoning.
- 企业级合规认证。

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试
- 企业客户支持

## 참고문헌

- [Command R+ (08-2024) 문서](https://docs.cohere.com/docs)
- 출시일: 2024-08-13
- 공급업체: Cohere
