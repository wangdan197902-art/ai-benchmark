---
title: "GPT-4 Turbo: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 Turbo performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-06
lastmod: 2023-11-06
draft: false
weight: 10
model_id: "gpt-4-turbo"
vendor: "openai"
version: "turbo"
tags: ["flagship", "multimodal", "long-context"]
---

# GPT-4 Turbo

## 모델 개요

OpenAI GPT-4 Turbo 模型, 128K 上下文窗口, 支持视觉输入, 相比 GPT-4 价格降低 3 倍, 性能提升。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | turbo | 2023-11-06 | 128K | text, image | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.4 | % | 5-shot |
| HumanEval | 80.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 85.2 | % | 0-shot CoT |
| MATH | 50.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.5 | % | 3-shot CoT |
| GPQA | 49.2 | % | 0-shot |
| IFEval | 77.9 | % | prompt_strict |
| ARC | 94.2 | % | challenge |
| MUSR | 61.1 | % | 0-shot |
| WinoGrande | 80.8 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 84.4, strong knowledge reasoning.
- HumanEval 80.5, excellent code generation.
- GSM8K 85.2, robust math reasoning.
- 支持文本、图像、音频多模态输入。
- 上下文窗口 128K，支持长文本。

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试
- 长文档摘要
- 视觉与图像理解
- Agent 工作流与工具调用

## 참고문헌

- [GPT-4 Turbo 문서](https://platform.openai.com/docs/models)
- 출시일: 2023-11-06
- 공급업체: Openai
