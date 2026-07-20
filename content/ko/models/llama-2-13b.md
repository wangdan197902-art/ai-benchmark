---
title: "Llama 2 13B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 2 13B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-07-18
lastmod: 2023-07-18
draft: false
weight: 10
model_id: "llama-2-13b"
vendor: "meta"
version: "2-13b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Llama 2 13B

## 모델 개요

Meta Llama 2 13B 中型开源模型, 4K 上下文, 13B 参数, 平衡性能与资源消耗, 适合中等规模部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 2-13b | 2023-07-18 | 4K | text | text | Llama 2 Community License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 56.4 | % | 5-shot |
| HumanEval | 40.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 34.6 | % | 0-shot CoT |
| MATH | 25.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.1 | % | 3-shot CoT |
| GPQA | 22.3 | % | 0-shot |
| IFEval | 49.9 | % | prompt_strict |
| ARC | 89.5 | % | challenge |
| MUSR | 33.8 | % | 0-shot |
| WinoGrande | 76.4 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- MMLU 仅 56.4，知识推理偏弱。
- HumanEval 40.7，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Llama 2 13B 문서](https://llama.meta.com/docs/)
- 출시일: 2023-07-18
- 공급업체: Meta
