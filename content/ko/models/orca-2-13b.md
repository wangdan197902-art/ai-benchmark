---
title: "Orca 2 13B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Orca 2 13B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-20
lastmod: 2023-11-20
draft: false
weight: 10
model_id: "orca-2-13b"
vendor: "other"
version: "orca-2-13b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Orca 2 13B

## 모델 개요

Microsoft Orca 2 13B 推理增强模型, 4K 上下文, 基于 Llama 2 微调, 通过渐进式复杂任务训练提升推理。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | orca-2-13b | 2023-11-20 | 4K | text | text | MIT |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.4 | % | 5-shot |
| HumanEval | 74.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.1 | % | 0-shot CoT |
| MATH | 42.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.8 | % | 3-shot CoT |
| GPQA | 42.5 | % | 0-shot |
| IFEval | 74.2 | % | prompt_strict |
| ARC | 91.4 | % | challenge |
| MUSR | 59.8 | % | 0-shot |
| WinoGrande | 80.2 | % | 0-shot |

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

- [Orca 2 13B 문서](https://huggingface.co/models)
- 출시일: 2023-11-20
- 공급업체: Other
