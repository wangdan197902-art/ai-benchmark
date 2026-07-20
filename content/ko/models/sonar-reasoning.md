---
title: "Sonar Reasoning: Complete Benchmark Performance Guide"
description: "In-depth analysis of Sonar Reasoning performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-12-18
lastmod: 2024-12-18
draft: false
weight: 10
model_id: "sonar-reasoning"
vendor: "other"
version: "sonar-reasoning"
tags: ["rag", "reasoning"]
---

# Sonar Reasoning

## 모델 개요

Perplexity Sonar Reasoning 推理型在线 RAG 模型, 127K 上下文, 基于 DeepSeek R1 微调, 链式思维推理。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | sonar-reasoning | 2024-12-18 | 127K | text | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 87.7 | % | 5-shot |
| HumanEval | 81.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 89.8 | % | 0-shot CoT |
| MATH | 50.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.4 | % | 3-shot CoT |
| GPQA | 50.1 | % | 0-shot |
| IFEval | 83.1 | % | prompt_strict |
| ARC | 96.2 | % | challenge |
| MUSR | 69.4 | % | 0-shot |
| WinoGrande | 87.2 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 87.7, strong knowledge reasoning.
- HumanEval 81.1, excellent code generation.
- GSM8K 89.8, robust math reasoning.

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试

## 참고문헌

- [Sonar Reasoning 문서](https://huggingface.co/models)
- 출시일: 2024-12-18
- 공급업체: Other
