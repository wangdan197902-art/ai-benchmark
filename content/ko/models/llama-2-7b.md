---
title: "Llama 2 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 2 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-07-18
lastmod: 2023-07-18
draft: false
weight: 10
model_id: "llama-2-7b"
vendor: "meta"
version: "2-7b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Llama 2 7B

## 모델 개요

Meta Llama 2 7B 经济型开源模型, 4K 上下文, 7B 参数, 广泛用于本地部署与微调基座。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 2-7b | 2023-07-18 | 4K | text | text | Llama 2 Community License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 70.8 | % | 5-shot |
| HumanEval | 42.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 31.0 | % | 0-shot CoT |
| MATH | 19.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 54.7 | % | 3-shot CoT |
| GPQA | 23.1 | % | 0-shot |
| IFEval | 58.5 | % | prompt_strict |
| ARC | 86.5 | % | challenge |
| MUSR | 35.3 | % | 0-shot |
| WinoGrande | 77.2 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- HumanEval 42.6，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Llama 2 7B 문서](https://llama.meta.com/docs/)
- 출시일: 2023-07-18
- 공급업체: Meta
