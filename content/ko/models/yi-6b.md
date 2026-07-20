---
title: "Yi 6B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Yi 6B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-05
lastmod: 2023-11-05
draft: false
weight: 10
model_id: "yi-6b"
vendor: "other"
version: "yi-6b"
tags: ["open-weights", "chinese", "self-hostable", "legacy"]
---

# Yi 6B

## 모델 개요

01.AI Yi 6B 经济型首代模型, 4K 上下文, 6B 参数, 适合本地部署与研究用途。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | yi-6b | 2023-11-05 | 4K | text | text | Apache 2.0 |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 68.0 | % | 5-shot |
| HumanEval | 42.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 37.0 | % | 0-shot CoT |
| MATH | 29.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 55.3 | % | 3-shot CoT |
| GPQA | 26.3 | % | 0-shot |
| IFEval | 54.9 | % | prompt_strict |
| ARC | 88.4 | % | challenge |
| MUSR | 29.5 | % | 0-shot |
| WinoGrande | 72.2 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- HumanEval 42.3，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Yi 6B 문서](https://huggingface.co/models)
- 출시일: 2023-11-05
- 공급업체: Other
