---
title: "DeepSeek Math 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek Math 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-06
lastmod: 2024-02-06
draft: false
weight: 10
model_id: "deepseek-math-7b"
vendor: "deepseek"
version: "math-7b"
tags: ["open-weights", "math", "self-hostable"]
---

# DeepSeek Math 7B

## 모델 개요

DeepSeek Math 7B 数学专用开源模型, 4K 上下文, 在 MATH 基准上达到 64.7%, 7B 规模数学模型领先。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | math-7b | 2024-02-06 | 4K | text | text | DeepSeek License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.3 | % | 5-shot |
| HumanEval | 54.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.1 | % | 0-shot CoT |
| MATH | 53.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.9 | % | 3-shot CoT |
| GPQA | 40.5 | % | 0-shot |
| IFEval | 61.1 | % | prompt_strict |
| ARC | 90.5 | % | challenge |
| MUSR | 49.8 | % | 0-shot |
| WinoGrande | 79.2 | % | 0-shot |

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

- 通用对话与问答

## 참고문헌

- [DeepSeek Math 7B 문서](https://api-docs.deepseek.com/)
- 출시일: 2024-02-06
- 공급업체: Deepseek
