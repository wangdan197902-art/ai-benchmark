---
title: "StarCoder2 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StarCoder2 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-28
lastmod: 2024-02-28
draft: false
weight: 10
model_id: "starcoder2-7b"
vendor: "other"
version: "starcoder2-7b"
tags: ["open-weights", "coding", "self-hostable"]
---

# StarCoder2 7B

## 모델 개요

BigCode StarCoder2 7B 经济型代码模型, 16K 上下文, 7B 参数, 适合本地代码补全与生成。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | starcoder2-7b | 2024-02-28 | 16K | text | text | BigCode Open Model License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 67.4 | % | 5-shot |
| HumanEval | 74.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 65.0 | % | 0-shot CoT |
| MATH | 30.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.0 | % | 3-shot CoT |
| GPQA | 33.6 | % | 0-shot |
| IFEval | 54.0 | % | prompt_strict |
| ARC | 90.5 | % | challenge |
| MUSR | 38.3 | % | 0-shot |
| WinoGrande | 73.1 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## 사용 사례

- 代码生成与调试

## 참고문헌

- [StarCoder2 7B 문서](https://huggingface.co/models)
- 출시일: 2024-02-28
- 공급업체: Other
