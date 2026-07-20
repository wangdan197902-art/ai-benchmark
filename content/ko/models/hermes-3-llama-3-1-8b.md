---
title: "Hermes 3 Llama 3.1 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Hermes 3 Llama 3.1 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "hermes-3-llama-3-1-8b"
vendor: "other"
version: "hermes-3-llama-3-1-8b"
tags: ["open-weights", "self-hostable"]
---

# Hermes 3 Llama 3.1 8B

## 모델 개요

NousResearch Hermes 3 Llama 3.1 8B 微调模型, 131K 上下文, 经济型开源模型, 适合本地部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | hermes-3-llama-3-1-8b | 2024-08-12 | 131K | text | text | Llama 3.1 Community License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 73.1 | % | 5-shot |
| HumanEval | 67.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 72.9 | % | 0-shot CoT |
| MATH | 25.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.6 | % | 3-shot CoT |
| GPQA | 31.5 | % | 0-shot |
| IFEval | 60.7 | % | prompt_strict |
| ARC | 88.7 | % | challenge |
| MUSR | 38.0 | % | 0-shot |
| WinoGrande | 78.1 | % | 0-shot |

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

- [Hermes 3 Llama 3.1 8B 문서](https://huggingface.co/models)
- 출시일: 2024-08-12
- 공급업체: Other
