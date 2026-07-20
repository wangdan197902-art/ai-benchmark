---
title: "Llama 3.2 3B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.2 3B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-25
lastmod: 2024-09-25
draft: false
weight: 10
model_id: "llama-3-2-3b"
vendor: "meta"
version: "3.2-3b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3.2 3B

## 모델 개요

Meta Llama 3.2 3B 轻量开源模型, 128K 上下文, 3B 参数, 适合移动设备与边缘部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.2-3b | 2024-09-25 | 128K | text | text | Llama 3.2 Community License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 52.5 | % | 5-shot |
| HumanEval | 42.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 46.4 | % | 0-shot CoT |
| MATH | 10.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 46.0 | % | 3-shot CoT |
| GPQA | 18.8 | % | 0-shot |
| IFEval | 48.6 | % | prompt_strict |
| ARC | 76.3 | % | challenge |
| MUSR | 29.3 | % | 0-shot |
| WinoGrande | 67.8 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- MMLU 仅 52.5，知识推理偏弱。
- HumanEval 42.5，代码能力较弱。
- 闭源专有模型，不支持自托管。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Llama 3.2 3B 문서](https://llama.meta.com/docs/)
- 출시일: 2024-09-25
- 공급업체: Meta
