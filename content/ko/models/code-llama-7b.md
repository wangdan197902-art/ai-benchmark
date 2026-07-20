---
title: "Code Llama 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Code Llama 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-08-24
lastmod: 2023-08-24
draft: false
weight: 10
model_id: "code-llama-7b"
vendor: "meta"
version: "code-llama-7b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Code Llama 7B

## 모델 개요

Meta Code Llama 7B 代码专用开源模型, 16K 上下文, 7B 参数, 适合本地代码补全与生成。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | code-llama-7b | 2023-08-24 | 16K | text | text | Llama 2 Community License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.5 | % | 5-shot |
| HumanEval | 76.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 52.2 | % | 0-shot CoT |
| MATH | 47.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.9 | % | 3-shot CoT |
| GPQA | 29.5 | % | 0-shot |
| IFEval | 61.2 | % | prompt_strict |
| ARC | 90.1 | % | challenge |
| MUSR | 42.9 | % | 0-shot |
| WinoGrande | 76.3 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- MMLU 仅 58.5，知识推理偏弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## 사용 사례

- 代码生成与调试

## 참고문헌

- [Code Llama 7B 문서](https://llama.meta.com/docs/)
- 출시일: 2023-08-24
- 공급업체: Meta
