---
title: "Phi-3.5 MoE: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3.5 MoE performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-16
lastmod: 2024-08-16
draft: false
weight: 10
model_id: "phi-3-5-moe"
vendor: "other"
version: "phi-3-5-moe"
tags: ["open-weights", "moe", "self-hostable"]
---

# Phi-3.5 MoE

## 모델 개요

Microsoft Phi-3.5 MoE 42B 混合专家模型, 128K 上下文, 总参 42B/活跃 6.6B, 性能接近 70B 稠密模型。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-5-moe | 2024-08-16 | 128K | text | text | MIT |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.7 | % | 5-shot |
| HumanEval | 69.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.5 | % | 0-shot CoT |
| MATH | 38.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.4 | % | 3-shot CoT |
| GPQA | 40.2 | % | 0-shot |
| IFEval | 74.3 | % | prompt_strict |
| ARC | 91.9 | % | challenge |
| MUSR | 50.3 | % | 0-shot |
| WinoGrande | 78.3 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 采用 MoE 混合专家架构。

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Phi-3.5 MoE 문서](https://huggingface.co/models)
- 출시일: 2024-08-16
- 공급업체: Other
