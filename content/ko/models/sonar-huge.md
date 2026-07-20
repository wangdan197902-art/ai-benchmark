---
title: "Sonar Huge: Complete Benchmark Performance Guide"
description: "In-depth analysis of Sonar Huge performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "sonar-huge"
vendor: "other"
version: "sonar-huge"
tags: ["rag", "enterprise", "reasoning"]
---

# Sonar Huge

## 모델 개요

Perplexity Sonar Huge 旗舰在线 RAG 模型, 127K 上下文, 基于 Llama 3.1 405B 微调, 推理能力最强。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | sonar-huge | 2024-08-13 | 127K | text | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.0 | % | 5-shot |
| HumanEval | 75.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 90.4 | % | 0-shot CoT |
| MATH | 46.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.6 | % | 3-shot CoT |
| GPQA | 46.7 | % | 0-shot |
| IFEval | 78.7 | % | prompt_strict |
| ARC | 94.8 | % | challenge |
| MUSR | 55.4 | % | 0-shot |
| WinoGrande | 87.7 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 81.0, strong knowledge reasoning.
- GSM8K 90.4, robust math reasoning.
- 企业级合规认证。

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试
- 企业客户支持

## 참고문헌

- [Sonar Huge 문서](https://huggingface.co/models)
- 출시일: 2024-08-13
- 공급업체: Other
