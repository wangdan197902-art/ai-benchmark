---
title: "Phi-1.5: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-1.5 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-14
lastmod: 2023-09-14
draft: false
weight: 10
model_id: "phi-1-5"
vendor: "other"
version: "phi-1-5"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Phi-1.5

## 모델 개요

Microsoft Phi-1.5 1.3B 模型, 2K 上下文, 改进推理能力, 在 1.3B 规模上接近 7B 模型水平。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-1-5 | 2023-09-14 | 2K | text | text | MIT |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.4 | % | 5-shot |
| HumanEval | 39.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 34.2 | % | 0-shot CoT |
| MATH | 27.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 49.5 | % | 3-shot CoT |
| GPQA | 16.9 | % | 0-shot |
| IFEval | 48.0 | % | prompt_strict |
| ARC | 75.9 | % | challenge |
| MUSR | 30.3 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- MMLU 仅 58.4，知识推理偏弱。
- HumanEval 39.2，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Phi-1.5 문서](https://huggingface.co/models)
- 출시일: 2023-09-14
- 공급업체: Other
