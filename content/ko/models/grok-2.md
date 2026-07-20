---
title: "Grok-2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Grok-2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "grok-2"
vendor: "xai"
version: "2"
tags: ["flagship", "multimodal", "realtime"]
---

# Grok-2

## 모델 개요

xAI Grok-2 是 xAI 旗舰模型，131K 上下文窗口，支持文本与图像输入，在 MMLU、HumanEval、MATH 等基准上接近头部闭源模型，集成于 X 平台提供实时信息。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Xai | 2 | 2024-08-13 | 131K | text, image | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 87.5 | % | 5-shot |
| HumanEval | 88.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 93.2 | % | 0-shot CoT |
| MATH | 76.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 84.0 | % | 3-shot CoT |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 87.5, strong knowledge reasoning.
- HumanEval 88.4, excellent code generation.
- GSM8K 93.2, robust math reasoning.
- 支持文本、图像、音频多模态输入。

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## 참고문헌

- [Grok-2 문서](https://docs.x.ai/)
- 출시일: 2024-08-13
- 공급업체: Xai
