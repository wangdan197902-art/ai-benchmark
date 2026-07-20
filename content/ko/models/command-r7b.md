---
title: "Command R7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Command R7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "command-r7b"
vendor: "cohere"
version: "r7b"
tags: ["open-weights", "rag", "self-hostable"]
---

# Command R7B

## 모델 개요

Cohere Command R7B 轻量开源模型, 128K 上下文, 7B 参数, 为 RAG 与工具调用优化, 适合边缘部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | r7b | 2024-08-13 | 128K | text | text | CC-BY-NC-4.0 |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.9 | % | 5-shot |
| HumanEval | 50.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 69.7 | % | 0-shot CoT |
| MATH | 40.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.1 | % | 3-shot CoT |
| GPQA | 30.9 | % | 0-shot |
| IFEval | 67.2 | % | prompt_strict |
| ARC | 90.7 | % | challenge |
| MUSR | 47.0 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

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

- [Command R7B 문서](https://docs.cohere.com/docs)
- 출시일: 2024-08-13
- 공급업체: Cohere
