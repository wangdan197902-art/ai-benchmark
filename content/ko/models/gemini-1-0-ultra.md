---
title: "Gemini 1.0 Ultra: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.0 Ultra performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-06
lastmod: 2023-12-06
draft: false
weight: 10
model_id: "gemini-1-0-ultra"
vendor: "google"
version: "1.0-ultra"
tags: ["flagship", "multimodal", "legacy"]
---

# Gemini 1.0 Ultra

## 모델 개요

Google Gemini 1.0 Ultra 旗舰模型, 32K 上下文, 在多项基准上接近 GPT-4, 多模态推理能力突出。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.0-ultra | 2023-12-06 | 32K | text, image | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.3 | % | 5-shot |
| HumanEval | 81.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 85.9 | % | 0-shot CoT |
| MATH | 57.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.8 | % | 3-shot CoT |
| GPQA | 46.9 | % | 0-shot |
| IFEval | 81.6 | % | prompt_strict |
| ARC | 95.7 | % | challenge |
| MUSR | 64.3 | % | 0-shot |
| WinoGrande | 80.4 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 80.3, strong knowledge reasoning.
- HumanEval 81.7, excellent code generation.
- GSM8K 85.9, robust math reasoning.
- 支持文本、图像、音频多模态输入。

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## 참고문헌

- [Gemini 1.0 Ultra 문서](https://ai.google.dev/gemini-api/docs)
- 출시일: 2023-12-06
- 공급업체: Google
