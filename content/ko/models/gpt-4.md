---
title: "GPT-4: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-03-14
lastmod: 2023-03-14
draft: false
weight: 10
model_id: "gpt-4"
vendor: "openai"
version: "4"
tags: ["flagship", "reasoning"]
---

# GPT-4

## 모델 개요

OpenAI GPT-4 大型语言模型, 8K 上下文, 在推理/创意/协作任务上显著超越 GPT-3.5, 首次引入人类水平表现。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4 | 2023-03-14 | 8K | text | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 85.8 | % | 5-shot |
| HumanEval | 77.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 91.7 | % | 0-shot CoT |
| MATH | 43.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 80.9 | % | 3-shot CoT |
| GPQA | 39.2 | % | 0-shot |
| IFEval | 74.6 | % | prompt_strict |
| ARC | 94.1 | % | challenge |
| MUSR | 54.6 | % | 0-shot |
| WinoGrande | 80.3 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 85.8, strong knowledge reasoning.
- GSM8K 91.7, robust math reasoning.

## 약점

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## 사용 사례

- 代码生成与调试
- Agent 工作流与工具调用

## 참고문헌

- [GPT-4 문서](https://platform.openai.com/docs/models)
- 출시일: 2023-03-14
- 공급업체: Openai
