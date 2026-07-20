---
title: "GPT-4 Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-25
lastmod: 2024-01-25
draft: false
weight: 10
model_id: "gpt-4-vision"
vendor: "openai"
version: "4-vision"
tags: ["multimodal", "flagship"]
---

# GPT-4 Vision

## 모델 개요

OpenAI GPT-4 Vision 正式版, 支持图像理解与多模态推理, 128K 上下文窗口。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-vision | 2024-01-25 | 128K | text, image | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.9 | % | 5-shot |
| HumanEval | 75.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.6 | % | 0-shot CoT |
| MATH | 48.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 80.9 | % | 3-shot CoT |
| GPQA | 41.8 | % | 0-shot |
| IFEval | 73.5 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 51.2 | % | 0-shot |
| WinoGrande | 86.9 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 83.9, strong knowledge reasoning.
- 支持文本、图像、音频多模态输入。

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## 참고문헌

- [GPT-4 Vision 문서](https://platform.openai.com/docs/models)
- 출시일: 2024-01-25
- 공급업체: Openai
