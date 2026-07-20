---
title: "Mistral Large: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Large performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-26
lastmod: 2024-02-26
draft: false
weight: 10
model_id: "mistral-large"
vendor: "mistral"
version: "large"
tags: ["flagship", "eu-residency"]
---

# Mistral Large

## 모델 개요

Mistral AI Large 首代旗舰, 32K 上下文, 多语言与推理能力突出, 原生支持函数调用与 JSON 输出。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | large | 2024-02-26 | 32K | text | text | Apache 2.0 |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.0 | % | 5-shot |
| HumanEval | 73.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 80.9 | % | 0-shot CoT |
| MATH | 49.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.7 | % | 3-shot CoT |
| GPQA | 38.1 | % | 0-shot |
| IFEval | 75.8 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 52.1 | % | 0-shot |
| WinoGrande | 83.3 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 82.0, strong knowledge reasoning.

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试
- Agent 工作流与工具调用

## 참고문헌

- [Mistral Large 문서](https://docs.mistral.ai/)
- 출시일: 2024-02-26
- 공급업체: Mistral
