---
title: "Sonar Small: Complete Benchmark Performance Guide"
description: "In-depth analysis of Sonar Small performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
model_id: "sonar-small"
vendor: "other"
version: "sonar-small"
tags: ["rag", "realtime"]
---

# Sonar Small

## 모델 개요

Perplexity Sonar Small 经济型在线 RAG 模型, 128K 上下文, 基于 Llama 3 8B 微调, 速度快成本低。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | sonar-small | 2024-05-13 | 128K | text | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.0 | % | 5-shot |
| HumanEval | 72.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.2 | % | 0-shot CoT |
| MATH | 43.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.7 | % | 3-shot CoT |
| GPQA | 34.5 | % | 0-shot |
| IFEval | 72.1 | % | prompt_strict |
| ARC | 91.7 | % | challenge |
| MUSR | 47.6 | % | 0-shot |
| WinoGrande | 81.4 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 80.0, strong knowledge reasoning.

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试

## 참고문헌

- [Sonar Small 문서](https://huggingface.co/models)
- 출시일: 2024-05-13
- 공급업체: Other
