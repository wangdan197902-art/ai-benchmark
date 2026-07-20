---
title: "Hermes 3 Llama 3.1 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Hermes 3 Llama 3.1 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "hermes-3-llama-3-1-70b"
vendor: "other"
version: "hermes-3-llama-3-1-70b"
tags: ["open-weights", "self-hostable"]
---

# Hermes 3 Llama 3.1 70B

## 모델 개요

NousResearch Hermes 3 Llama 3.1 70B 微调模型, 131K 上下文, 改进指令遵循与中立性。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | hermes-3-llama-3-1-70b | 2024-08-12 | 131K | text | text | Llama 3.1 Community License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.7 | % | 5-shot |
| HumanEval | 75.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 76.4 | % | 0-shot CoT |
| MATH | 54.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.9 | % | 3-shot CoT |
| GPQA | 30.1 | % | 0-shot |
| IFEval | 73.8 | % | prompt_strict |
| ARC | 91.4 | % | challenge |
| MUSR | 55.4 | % | 0-shot |
| WinoGrande | 83.9 | % | 0-shot |

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

- [Hermes 3 Llama 3.1 70B 문서](https://huggingface.co/models)
- 출시일: 2024-08-12
- 공급업체: Other
