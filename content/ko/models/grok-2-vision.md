---
title: "Grok-2 Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of Grok-2 Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "grok-2-vision"
vendor: "xai"
version: "2-vision"
tags: ["multimodal"]
---

# Grok-2 Vision

## 모델 개요

xAI Grok-2 Vision 多模态模型, 32K 上下文, 支持图像理解, 适合视觉问答与多模态推理。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Xai | 2-vision | 2024-08-13 | 32K | text, image | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.4 | % | 5-shot |
| HumanEval | 84.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.4 | % | 0-shot CoT |
| MATH | 41.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.4 | % | 3-shot CoT |
| GPQA | 43.8 | % | 0-shot |
| IFEval | 76.9 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 57.7 | % | 0-shot |
| WinoGrande | 87.5 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 83.4, strong knowledge reasoning.
- HumanEval 84.2, excellent code generation.
- 支持文本、图像、音频多模态输入。

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试
- 视觉与图像理解

## 참고문헌

- [Grok-2 Vision 문서](https://docs.x.ai/)
- 출시일: 2024-08-13
- 공급업체: Xai
