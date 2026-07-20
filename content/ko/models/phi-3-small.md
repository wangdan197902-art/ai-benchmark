---
title: "Phi-3 Small: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3 Small performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-21
lastmod: 2024-05-21
draft: false
weight: 10
model_id: "phi-3-small"
vendor: "other"
version: "phi-3-small"
tags: ["open-weights", "self-hostable"]
---

# Phi-3 Small

## 모델 개요

Microsoft Phi-3 Small 7.4B 模型, 8K 上下文, 在 7B 规模上推理能力突出, 适合移动设备部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-small | 2024-05-21 | 8K | text | text | MIT |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 71.8 | % | 5-shot |
| HumanEval | 68.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 62.7 | % | 0-shot CoT |
| MATH | 43.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.8 | % | 3-shot CoT |
| GPQA | 30.9 | % | 0-shot |
| IFEval | 61.0 | % | prompt_strict |
| ARC | 89.6 | % | challenge |
| MUSR | 36.5 | % | 0-shot |
| WinoGrande | 74.9 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Phi-3 Small 문서](https://huggingface.co/models)
- 출시일: 2024-05-21
- 공급업체: Other
