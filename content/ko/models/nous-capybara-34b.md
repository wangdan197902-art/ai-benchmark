---
title: "Nous Capybara 34B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Nous Capybara 34B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-15
lastmod: 2023-11-15
draft: false
weight: 10
model_id: "nous-capybara-34b"
vendor: "other"
version: "nous-capybara-34b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Nous Capybara 34B

## 모델 개요

NousResearch Capybara 34B 对话模型, 4K 上下文, 基于 Yi 34B 微调, 改进长对话与推理能力。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-capybara-34b | 2023-11-15 | 4K | text | text | Apache 2.0 |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 53.2 | % | 5-shot |
| HumanEval | 50.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 31.9 | % | 0-shot CoT |
| MATH | 23.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 56.1 | % | 3-shot CoT |
| GPQA | 29.7 | % | 0-shot |
| IFEval | 52.9 | % | prompt_strict |
| ARC | 80.7 | % | challenge |
| MUSR | 31.7 | % | 0-shot |
| WinoGrande | 67.3 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- MMLU 仅 53.2，知识推理偏弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Nous Capybara 34B 문서](https://huggingface.co/models)
- 출시일: 2023-11-15
- 공급업체: Other
