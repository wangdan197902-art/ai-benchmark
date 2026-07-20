---
title: "Flan-T5 XL: Complete Benchmark Performance Guide"
description: "In-depth analysis of Flan-T5 XL performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2022-12-07
lastmod: 2022-12-07
draft: false
weight: 10
model_id: "flan-t5-xl"
vendor: "other"
version: "flan-t5-xl"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Flan-T5 XL

## 모델 개요

Google Flan-T5 XL 3B 指令微调模型, 4K 上下文, 基于多任务指令微调, 适合零样本泛化任务。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | flan-t5-xl | 2022-12-07 | 4K | text | text | Apache 2.0 |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 60.4 | % | 5-shot |
| HumanEval | 34.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 46.5 | % | 0-shot CoT |
| MATH | 27.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 52.5 | % | 3-shot CoT |
| GPQA | 22.6 | % | 0-shot |
| IFEval | 55.7 | % | prompt_strict |
| ARC | 88.0 | % | challenge |
| MUSR | 40.2 | % | 0-shot |
| WinoGrande | 75.5 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- HumanEval 34.0，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Flan-T5 XL 문서](https://huggingface.co/models)
- 출시일: 2022-12-07
- 공급업체: Other
