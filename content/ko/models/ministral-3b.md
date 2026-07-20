---
title: "Ministral 3B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Ministral 3B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-16
lastmod: 2024-10-16
draft: false
weight: 10
model_id: "ministral-3b"
vendor: "mistral"
version: "ministral-3b"
tags: ["open-weights", "self-hostable", "long-context"]
---

# Ministral 3B

## 모델 개요

Mistral Ministral 3B 超轻量边缘模型, 128K 上下文, 3B 参数, 最具性价比的边缘部署模型。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | ministral-3b | 2024-10-16 | 128K | text | text | Mistral Research License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 42.4 | % | 5-shot |
| HumanEval | 37.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 32.2 | % | 0-shot CoT |
| MATH | 10.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.1 | % | 3-shot CoT |
| GPQA | 19.0 | % | 0-shot |
| IFEval | 47.8 | % | prompt_strict |
| ARC | 81.5 | % | challenge |
| MUSR | 29.4 | % | 0-shot |
| WinoGrande | 64.8 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 上下文窗口 128K，支持长文本。

## 약점

- MMLU 仅 42.4，知识推理偏弱。
- HumanEval 37.2，代码能力较弱。
- 闭源专有模型，不支持自托管。

## 사용 사례

- 长文档摘要

## 참고문헌

- [Ministral 3B 문서](https://docs.mistral.ai/)
- 출시일: 2024-10-16
- 공급업체: Mistral
