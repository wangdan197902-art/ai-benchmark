---
title: "Flan-UL2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Flan-UL2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-03-03
lastmod: 2023-03-03
draft: false
weight: 10
model_id: "flan-ul2"
vendor: "other"
version: "flan-ul2"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Flan-UL2

## 모델 개요

Google Flan-UL2 20B 指令微调模型, 4K 上下文, 基于 UL2 框架, 适合多任务与零样本推理。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | flan-ul2 | 2023-03-03 | 4K | text | text | Apache 2.0 |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.7 | % | 5-shot |
| HumanEval | 46.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 40.6 | % | 0-shot CoT |
| MATH | 22.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 49.2 | % | 3-shot CoT |
| GPQA | 27.2 | % | 0-shot |
| IFEval | 55.6 | % | prompt_strict |
| ARC | 88.8 | % | challenge |
| MUSR | 37.2 | % | 0-shot |
| WinoGrande | 76.2 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- MMLU 仅 58.7，知识推理偏弱。
- HumanEval 46.8，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Flan-UL2 문서](https://huggingface.co/models)
- 출시일: 2023-03-03
- 공급업체: Other
