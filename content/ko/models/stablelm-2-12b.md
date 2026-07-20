---
title: "StableLM 2 12B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StableLM 2 12B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-19
lastmod: 2024-01-19
draft: false
weight: 10
model_id: "stablelm-2-12b"
vendor: "other"
version: "stablelm-2-12b"
tags: ["open-weights", "self-hostable"]
---

# StableLM 2 12B

## 모델 개요

Stability AI StableLM 2 12B 模型, 4K 上下文, 多语言训练, 支持 7 种语言, 性能接近 Llama 2 13B。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | stablelm-2-12b | 2024-01-19 | 4K | text | text | Stability AI Community License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.7 | % | 5-shot |
| HumanEval | 76.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.1 | % | 0-shot CoT |
| MATH | 37.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.6 | % | 3-shot CoT |
| GPQA | 44.0 | % | 0-shot |
| IFEval | 80.0 | % | prompt_strict |
| ARC | 94.9 | % | challenge |
| MUSR | 58.1 | % | 0-shot |
| WinoGrande | 84.1 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 사용 사례

- 代码生成与调试

## 참고문헌

- [StableLM 2 12B 문서](https://huggingface.co/models)
- 출시일: 2024-01-19
- 공급업체: Other
