---
title: "StableLM 2 1.6B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StableLM 2 1.6B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-19
lastmod: 2024-01-19
draft: false
weight: 10
model_id: "stablelm-2-1-6b"
vendor: "other"
version: "stablelm-2-1-6b"
tags: ["open-weights", "self-hostable"]
---

# StableLM 2 1.6B

## 모델 개요

Stability AI StableLM 2 1.6B 轻量模型, 4K 上下文, 多语言训练, 适合移动设备部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | stablelm-2-1-6b | 2024-01-19 | 4K | text | text | Stability AI Community License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 52.7 | % | 5-shot |
| HumanEval | 37.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 43.5 | % | 0-shot CoT |
| MATH | 26.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 40.7 | % | 3-shot CoT |
| GPQA | 15.0 | % | 0-shot |
| IFEval | 44.1 | % | prompt_strict |
| ARC | 77.7 | % | challenge |
| MUSR | 26.4 | % | 0-shot |
| WinoGrande | 70.3 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- MMLU 仅 52.7，知识推理偏弱。
- HumanEval 37.3，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [StableLM 2 1.6B 문서](https://huggingface.co/models)
- 출시일: 2024-01-19
- 공급업체: Other
