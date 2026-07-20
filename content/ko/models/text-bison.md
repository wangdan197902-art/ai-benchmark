---
title: "Text Bison: Complete Benchmark Performance Guide"
description: "In-depth analysis of Text Bison performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-05-10
lastmod: 2023-05-10
draft: false
weight: 10
model_id: "text-bison"
vendor: "google"
version: "text-bison"
tags: ["legacy"]
---

# Text Bison

## 모델 개요

Google Vertex AI Text Bison 文本生成模型, 基于 PaLM 2, 8K 上下文, 适合指令跟随与生成任务。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | text-bison | 2023-05-10 | 8K | text | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 53.9 | % | 5-shot |
| HumanEval | 45.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 42.8 | % | 0-shot CoT |
| MATH | 12.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.2 | % | 3-shot CoT |
| GPQA | 27.7 | % | 0-shot |
| IFEval | 59.5 | % | prompt_strict |
| ARC | 86.7 | % | challenge |
| MUSR | 40.8 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- MMLU 仅 53.9，知识推理偏弱。
- HumanEval 45.1，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Text Bison 문서](https://ai.google.dev/gemini-api/docs)
- 출시일: 2023-05-10
- 공급업체: Google
