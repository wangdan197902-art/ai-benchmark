---
title: "NVIDIA Llama 3.1 Nemotron 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of NVIDIA Llama 3.1 Nemotron 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-17
lastmod: 2024-10-17
draft: false
weight: 10
model_id: "nvidia-llama-3-1-nemotron-70b"
vendor: "other"
version: "nvidia-llama-3-1-nemotron-70b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# NVIDIA Llama 3.1 Nemotron 70B

## 모델 개요

NVIDIA Llama 3.1 Nemotron 70B, 131K 上下文, NVIDIA 优化 Llama 3.1, 在 Arena 上接近 GPT-4o。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nvidia-llama-3-1-nemotron-70b | 2024-10-17 | 131K | text | text | Llama 3.1 Community License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.4 | % | 5-shot |
| HumanEval | 66.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.8 | % | 0-shot CoT |
| MATH | 40.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.6 | % | 3-shot CoT |
| GPQA | 37.6 | % | 0-shot |
| IFEval | 69.6 | % | prompt_strict |
| ARC | 93.2 | % | challenge |
| MUSR | 47.7 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 80.4, strong knowledge reasoning.

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [NVIDIA Llama 3.1 Nemotron 70B 문서](https://huggingface.co/models)
- 출시일: 2024-10-17
- 공급업체: Other
